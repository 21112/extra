from os import system

def o(directory=" ",keys=" "):
    h=f'more <{directory}:{keys}'
    system(h)
    print("Got")

def i(shifr = " ",fo=" ",keys=" "):
    h=f'echo {shifr} > {fo}: {keys}'
    system(h)
    print("Finish")
