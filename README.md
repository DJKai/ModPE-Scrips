# ModPE-Scrips
**Some 'Commands' for a Mod Remeber all these nodes are Case Sensative**

**For the first command add: when making the mod don't leave big 'enter' as it will brake the code only one**

function procCmd(cmd){

cmd = cmd.toLowerCase();

}

**only add that ONCE at the top of the page.**
**To add a command add:**

if(cmd == "[command]"){

**Then if you want it to say somthing in the chat add**

clientMessage("[message]"):


**therefore if you put**

if(cmd == "Hi"){

clientMessage("Hello"):

}

**This will do:**

if you do /hi the chat will say Hello

between diffenent commands add } and when you finish the script add 

}

}
