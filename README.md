Java Logger 

    Used to efficiently log a server.
    Encodes log messages in a spatial effiecent way for
    servers that log a large number of things.
    
    Takes advantage of the fact that log messages are often 
    repatitive to save space.
    
    Easily searchable logs. Quickly and efficiently find log
    messages that apply to a specific class, tag, or time frame.
    
Downfalls of this Logger

    Longer time to see logs since they must be decoded.
    Have to run a program to decode the messages.
    Limited to 256 unique log messages, 256 unique class names and
    8 different serverities with current implementation.
    
    
    
    
    

