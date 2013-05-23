name to clipboard-service
=============

OSX finder service that copys the selected file's name to the clipboard

Service takes file/folder as input  
Run shell script (python - inputs passed as arguments):

    import sys
    
    s = sys.argv[1]
    x = s.rfind("/")
    s= s[x+1:]
    print s

copy to clipboard
