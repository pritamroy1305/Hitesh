# 📘 Modules in Node.js

 ### collection of code


 >Built in modules 

 >3rd Party (npm install)

 >Custom (my Own)


# ✨ File System (FS Module)
  ### it is a module that works on file system
   ### It is a object that has many func. 
       *we can see by console.log(fs)*

# Working 
### when node script.js is typed , node will read this file , which internally has a wrapper fnx , the source code is injectd inn wrapper fnx, which is not available in browser --> mantained by node.js team .
###first it checks if there is a 3rd party module , built in module , else throw ann error 
```reruie("./fs")
the ./ will search if there is any built in module in current directory --> not found so error 
require("x")
   │
   ├── 1. Core Module? → return it
   │
   ├── 2. Local File? (./, ../, /) → return it
   │
   ├── 3. node_modules? → search & return
   │
   └── 4. Else → Error: Cannot find module
