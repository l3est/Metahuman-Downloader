# Metahuman-Downloader
A Simple Metahuman Downloader for Unearl Engine 5

# How to use?
1. first download it from [here](https://github.com/l3est/Metahuman-Downloader/releases/tag/Release)
2. run MetaHuman Downloader.exe
3. open quixel.com and login. choose any metahuman you want
4. copy the assetId parameter from link (the part I highlighted here) and paste in in Metahuman Downloader: ![image](https://user-images.githubusercontent.com/8002505/233785847-4fac037f-db95-42de-a0ec-c6c9282ef2ee.png)
5. right click on quixel.com empty page area and click **Inspect** or **Inspect Element** (depends on your browser) and go to **Network** tab.
![image](https://user-images.githubusercontent.com/8002505/233786322-d6c3d656-7673-4dfe-b2b2-eb61f73ca29c.png)
![image](https://user-images.githubusercontent.com/8002505/233786345-5e82f169-7f3e-4aed-a35b-7b0dc96a76bc.png)
6. right click on the link that starts with **list** and select **Copy** -> **Copy as fetch**. if there is no link just press **F5** to refresh the page.
![image](https://user-images.githubusercontent.com/8002505/233786415-5989e4f7-e834-47f5-91d7-50b06199431e.png)
7. open a text editor like notepad and paste the text you just copied. find the "authorization" field and copy the text that I highlighted with **yellow** color. DON'T copy the "" before and after the text.
![image](https://user-images.githubusercontent.com/8002505/233786536-b931285f-c88b-4d42-b907-2c5ff1a7a3be.png)
8. paste the code in *Metahuman Downloader (in the big text area).
9. choose if the metahuman you're trying to download is public or private. private ones are the ones you've created and you can see them in [here](https://quixel.com/megascans/metahumans?category=my_metahumans_ue5). rest of them are public.
10. now click **Get Link**. the link will be copied to your clipboard. you can paste it in your Web Browser or Download Manager.
11. After downloading the zip file extract it and open the folder, you'll see a **MetaHumans** folder.
![image](https://user-images.githubusercontent.com/8002505/233787113-66982d24-d492-413e-af5b-13431215ff6c.png)
12. Close Unreal Engine and Copy that MetaHumans folder into the project you want (replace **YOUR_USERNAME** with your windows username and **PROJECT_NAME** with your Unreal Engine project name.) `C:\Users\YOUR_USERNAME\Documents\Unreal Projects\PROJECT_NAME\Content`

# How It works?
It works by using Bridge's private API.

# Why I made this?
I couldn't download the models using bridge plugin so I made this. it's faster and works every time!
