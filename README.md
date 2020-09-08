# cd
:)

# File

## ISFILE
\<Boolean\> isfile(\<string\> pathToFile)

### Description
Will return a true or false statement on if the file exist or not.

#### Example
```lua
if isfile("cd/Chat.txt") then
	print("File Exist")
else
	print("File Does Not Exist","Creating File!")
	writefile("cd/Chat.txt","")
end
```

## ISFOLDER
\<Boolean\> isfolder(\<string\> pathToDirectory)

### Description
Will return a true or false statement on if the folder exist or not. (Note: The way I wrote isfolder in the script makes it a little bit wack, but I will update it to be better, I promise :))

#### Example
```lua
if isfolder("cd") then
	print("Folder Exist")
else
	print("Folder Does Not Exist")
end
```

# In-Game Use

## RCHAT
\<void\> rchat(\<string\>)

### Description
Will run any game:GetService("Players").LocalPlayer.Chatted connections without saying anything in chat

#### Example
```lua
rchat(":respawn me")
```

## FCHAT
\<void\> fchat(\<string\>)

### Description
Will type in chat without hitting any game:GetService("Players").LocalPlayer.Chatted connections

#### Example
```lua
fchat("Hi.")
```

## TCHAT
\<void\> tchat(\<string\>)

### Description
Will use both rchat and fchat so if you want to use both the real chat and fake chat to simulate talking in game normally

#### Example
```lua
tchat("Hello.") 
```

# Experimental

## IS_CD_CALLER
\<Boolean\> is_cd_caller(\<void\>)

### Description
Returns true if you are using this API. It's a way to check if you have the API and working!

#### Example
```lua
if is_cd_caller then
	print("Found API!")
else
	print("Did Not Find API?","Call 586141923048161291 for help.")
end
```

# h
msg me if you have any useful functions that would just make life easier to me so I can add them
