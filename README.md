# Built-a-pin-extractor

def pin_extractor(poem):
    secret_code = ''
    lines = poem.split('\n')  
    for line in lines :
        print(line)
        words = line.split()
        print(words)

poem = """Stars and the moon
shine in the sky
white and bright
until the end of the night"""

print(pin_extractor(poem))
<br>
OUTPUT = Stars and the moon
['Stras', 'and', 'the', 'moon']
shine in the sky
['shine', 'in', 'the', 'sky']
white and bright
['white', 'and', 'bright']
until the end of the night
['until', 'the', 'end', 'of', 'the', 'night']
