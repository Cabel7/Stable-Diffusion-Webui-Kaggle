# **Kaggle** <br>
**Kaggle** is a subsidiary of Google, it is an online community of data scientists and machine learning engineers.

Kaggle allows users to find datasets they want to use in building AI models, publish datasets, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges.
But we are not here for this, are we ? (⁠.⁠ ⁠❛⁠ ⁠ᴗ⁠ ⁠❛⁠.⁠) <br>

**Kaggle Hardware Specifications**

| Hardware Component | Release_Year | Core_Count | Memory	| Hours/Week 
| --- | --- | --- | --- | --- |
NVIDIA_Tesla_P100_GPU |	2016 | 3584_Cuda_Cores | 16 GB | 32 h 
NVIDIA_T4_x2_GPU | 2018	| 2560_Cuda_Cores |	16 GB	| 32 h 
Google_TPU_v3-8	| 2018 |	8_TPU_v3_Cores	| 128 GB	| 20 h
Intel_Xeon_2.20_GHz_CPU	| 2016 | 4_vCPU_Cores |	32 GB	| Unlimited




# How to create a Kaggle account ? <br>
1. Go to the Kaggle website and click on sign up section. <br>
2. Setup your Kaggle profile by providing a brief bio, picture, location, title and current workplace. You can also add your LinkedIn, Github and Facebook accounts so people can contact you when needed. <br>

# Now comes the most crucial part <br>
**Account Verification** <br>
Without this you won't be able to use ***Kaggle GPU*** even after you sign up into Kaggle, so better verify <br>

**Follow These steps to verify your Kaggle account.** <br>
1. Go to your account profile and click on your Account; this will lead to a page that contains your account information.
2. Click “Edit Public Profile”.
3. Scroll down to “Phone Verification”, and click on the hyperlink: “Not Verified”.
4. "Once the phone number is sorted, check the CAPTCHA box to click the final button “Send verification code”
5. At this point, if you get a verification code, you can go ahead and finish up the verification process. However, if you get a message like this one below that states “This phone number cannot be verified”, or any other similar statement then click “Contact us for help” in the black panel on the right.
* If you encounter a statement like “This phone number has been used many times. Please try a different number”, it is because several attempts have been made to verify that particular number OR “You have exceeded the quota for this request. Please wait a bit and try again later”, it is because you have attempted the verification too many times in a short while, and you need to try at a later time. The important thing to note is that the same phone number verification issue elicited these responses, and trying out the steps in this infographic is sure to resolve it).
* A page full of possible issues you might encounter on Kaggle will pop up. We’ve found you receive a quicker response from Kaggle support if you select, “I found an issue with the website” under the category “other”. Clicking that will launch a sort of form for your complaint.
* Click on "I found an issue with verification".
* Fill out the required fields, check the CAPTCHA box, and click “Contact Support”
* All you can do right now is wait, and your request will typically get sorted in 24 hours.
* You most likely will receive a mail stating that you can now get your account verified. Log back into Kaggle to repeat steps 3 to 5.
* You should get a response soon enough. <br>

# How to run Stable Diffusion Webui ?<br>
1. First select any ***[Model](https://github.com/Cabel7/Stable-Diffusion-Webui-Kaggle)***
![IMG_20230626_133950](https://github.com/Cabel7/Image/assets/134921117/6cb14925-40c7-4a5f-938c-32cf7a924431)
2. It should redirect you to the notebook page; there you click on ***Copy & Edit*** option, it should redirect you to private kaggle kernel. ![Screenshot_2023-06-26-13-51-59-08_40deb401b9ffe8e1df2f1cc5ba480b12](https://github.com/Cabel7/Image/assets/134921117/443184be-f36e-419d-8524-a7dca4a3bffd)
3. After being redirected click on three dots available on the top right corner.
![IMG_20230626_141833](https://github.com/Cabel7/Image/assets/134921117/917d586e-5691-4882-94de-30446cc66fa1)
5. If you have verified your account already as mentioned above then should be able to see a notebook section there, click on it and select any of the two GPU provided.![IMG_20230626_142824](https://github.com/Cabel7/Image/assets/134921117/6bae14df-3b20-4639-ae4a-b48e8109f3f5)
7. After that scroll down and you would see an option for internet, turn it on.![IMG_20230626_143026](https://github.com/Cabel7/Image/assets/134921117/ddb0d886-0d63-4a79-bc96-2750bfa1c15f)
8. Set the environment to the latest one.
9. Then remove the hashes in front of the git extensions you want to use.<br>

   **Note:** Don't try to load all the git extension otherwise the machine would run out of memory, so put hash in front of those extension you don't want use atleast 4 to 5. <br>

10. And you are good to go ahead (⁠｡⁠•̀⁠ᴗ⁠-⁠)⁠✧

# Things to be noted before we move ahead <br>
* **How long do you want to run the Stable Diffusion Webui?**
* There are two ways by which you can run a notebook
  1. Interactive session
  2. Save & Run all (Commit)
> **Interactive Session:** When you click on Run All it starts an interactive session which automatically terminates after 40-60 minutes if you are not found active on Kaggle kernel. Choose this one if you want to run it for a short period of time. <br>
> **Save & Run all (Commit):** Save & Run all option runs your notebook untill it gets an output so if you are running the Stable diffusion Webui it will keep on running forever, so I prefer this one for longer runtime. <br>
***But please don't misuse it, cancel the session manually if you're done with your work.***

9. Click on Run All if you want to run for a short period of time.
![IMG_20230626_150813](https://github.com/Cabel7/Image/assets/134921117/1d18419e-9099-4776-b67c-b35d5637b82c)
10. For longer runtime click Save Version and then in Advanced Settings select run with GPU for all sessions and Save.
11. After that click on three horizontal lines on top left corner and then View active Events, there you can manage all your active sessions.
    ![IMG_20230626_151750](https://github.com/Cabel7/Image/assets/134921117/8fe08abb-ee20-4304-8728-568d1e3a3ec2)
12. Click on three dots and then view logs, it should redirect you to your notebook logs.
13. After 10-12 minutes of your your notebook execution scroll down in the notebook logs and look for the public url like this 🔻
    ![IMG_20230626_152925](https://github.com/Cabel7/Image/assets/134921117/3660a141-cc25-487b-8ea3-6dc769a392e9)
14. Copy paste that url into your web browser where you want to run the Stable Diffusion Webui and done.

**And Don't forget to cancel the session if you no longer need it.**

# Note:<br>
1. Kaggle is not like Google Colab so you can't mount Google drive like in kaggle there are many work arounds available for that on internet.
2. NSFW is strictly prohibited on Kaggle platform so don't try to use others public notebook for creating NSFW works, if you do you might get banned on kaggle.
    
