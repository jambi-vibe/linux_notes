## Remote machine access

#SSH

[ssh](./ssh.md)


## Common Linux Commands

#Filesystem Navigation

ls: list whats inthe current directory

Syntax:```ls <flags>```

Important Flags:-l; lists expanded listing with permissions, -h; makes the listings easier to read by humans, -a; lists all dir/files even hidden ones

cd: change directory

Syntax: ```cd <dir/file path>```

Important Concepts: "."; denotes the current directory, ".."; denotes the parent directory(one level up), "/"; denotes the root of the filesystem, "~"; denotes the root of the user specific filesystem


#File/dir parsing

Find: displays file paths of files meeting a specific criteria

Syntax: ```find <where to search> <flags>```

Important Flags: -type; specifies what you are looking for(f for file), -size; specifies the size to look for(xxxxc for bytes), !; denotes not, -executable; tests for permissions to see if it is executable


