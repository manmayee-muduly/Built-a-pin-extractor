# Built-a-pin-extractor

def pin_extractor(poem):
    secret_code = ''
    lines = poem.split('\n')  
    for line_index,line in enumerate(lines) :
        print(line_index,line)
        words = line.split()
        print(words)

poem = """Stars and the moon
shine in the sky
white and bright
until the end of the night"""

print(pin_extractor(poem))
<br>
OUTPUT = 
<br>
0 Stars and the moon
['Stras', 'and', 'the', 'moon']
1 shine in the sky
['shine', 'in', 'the', 'sky']
2 white and bright
['white', 'and', 'bright']
3 until the end of the night
['until', 'the', 'end', 'of', 'the', 'night']
