client-storage
==============

Local Storage interface to store/retrieve information on the client

Uses window.localStorage if supported with optional cookie fallback

Usage: 

    
    // This statement is optional - the second param (also optional) is to accept cookies as a fallback
    ClientStorage.Init("YourNameSpace", true); 

    ClientStorage.Set("YourKey", "Value - can be object, array, int, bool, anything!");

    ClientStorage.Get("YourKey", "Optional default return value - will be null if not set");

    ClientStorage.Remove("YourKey");
    
    
