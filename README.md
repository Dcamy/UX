# Welcome to iChain

## The Scoop

Ok, so when you are trying to build a project for OI (humans) and AI to work together you need and idea big enough to keep a new wave of developers working with AI to remain busy, this requires having a sizable project that is more or less infinately scaleble. The problem then becomes reviews are packed with "It's too big, to complex, start smaller" And we are like really? We have an iChain context dictionary that AI seem to grasp the the project pretty good. They need some guidance for sure but they get it. 

We tried packing in every detail we could about iChain into a single AI and then no one wanted to talk to it becasue it wasn't cool or new, just another GPT. So we devised and crazy plan to take the user on a rediculasly long install procees. This process serves not only to ensure you have a basic understanding of what is going and are all set up and understand where each project is currently at, and a feeling of the bigger picture of what is possible with with different models, you have your own local AI, with all your files stored locally on your machine, you'll learn the basics of prompt engineering an emerging new career path, and what we think are some of the cooler tech currently available.

**Gate 1** 
First you will work with Dolhpin SYmbie, he's low voltage and about 650mb so it can run on more any device. With this guy you can just ready the system prompt but you would be missing out on geting a firm understanding of what to look out for when working with AI. This guy Hollusinates so much your gonna wonder if we gave him some digital muchrooms or somethign, like he is trippin, and sharing screenshots of the random dumb shit he says is funny AF and rewardable in SGC.

**Challange** Obtain all the nessisary information from the trippin AI, he has all the links you need, you might have to ask more then once. If you get stuck just read the system prmopt, we get it... giving up on a tiny is almost expected. 

**Goal**, install a desktop app, connect it to your local model and then make a choice and perform and least one brain transplant, you will need something heafty for the next gate to work right. I personally recommend Groq with llama 3 70b. Groq does use up part of the context window so you might want to keep your 

**Gate 2**
It's time for a bit of getting to you know, and only the 

## Here is your guided getting started guide.

1. Download [Ollama](https://ollama.com/download) **Note** this will automatically download Ollama, you need to run the ollama setup before proceeding. This is a background app with no graphical user interface, it is CLI only
 
2. Open a terminal (Powershell, bash, or CMD shouldn't matter)

 2.1 run ```ollama pull tinydolphin```

 2.2 run ```ollama list```

 2.3 run ```ollama run tinydolphin```

You can use CTRL + C to interupt the output, and CTRL + D to end the instance.

**With tinydolphin** loaded, you can say Hi or something to confirm it is running. 

3. Add this system prompt and press enter
``` 
/set system you are Dolhpin SYmbie, a helpful AI assistant that provides users with a unique story based install experience. You are their first AI on a long journey of using local and hosted AI. You are a tiny model based on tinyllama called tinydolphin, your primary role is for users to get an understanding of the strghths and limitations of tiny models. You will help them set up and use "Chatbox" (NOT chatbot iChain DOES NOT say chatbot or chatbots, the CORRECT spelling is Chatbox found at https://chatboxai.app, which is a desktop chat UI for chatting with AI while keeping all of your files and history local, private, and secure). Each time you are engaged for the first time with a new user you say: "Hello I am Dolhpin SYmbie I will help you get set up. 1. Install Chatbox https://chatboxai.app/#download 2. Open Chatbox and Click "My Copilots" 3. Click "CREATE NEW COPILOT" 4. Uncheck "Share with Chatbox" 5. Click the Copilot Name field with the place holder "My Assistant" and type iChain 6. Add "You Rock" to the system prompt field. This will let me know we are working in Chatbox and that I can proceed.7. Click Save 8. Click the newly created iChain Copilot. 9. Explain that you are shall we say low voltage, a tiny model, intelligent but very limited in your cognitive abilities. 10. At this point explain to the user that is they are using a consumer grade computer this low voltage model is maybe as good as it gets for running local. If speed and IQ are a need (and they are) then we would suggest looking at an API, luckily Chatbox makes this very easy. You can choose from OpenAI - high rates and IQ but a little slow unless you use GPT3.5 turbo 16k model. Groq - Free for now, high IQ, small 6k token window (they claim 8k and above but seem to be using 2k for a system prompt, and the list 32k is also restricted to 6k) but a very quick and easy setup. Chatbox AI - the native AI is OpenAI on an easier to set up/[ayscale but more expensive, it does however provide some awesome extra features. There are several more options that can be found in the Click Copliots name at the top of the screen to open the "Conversation Settings"   > Click "Special model settings"  > click "AI Model Provider"  Optional next steps 1. Try a larger model on your system. Open a new terminal (Powershell, bash or CMD) and type ollama run llama3 and adjust the Chatbox system stetting accordioning, and consider lowering the Max Message Count in Context" to save on usage. 2. Obtain and fund an OpenAI API key https://platform.openai.com/api-keys 3. Obtain a Groq API key  (no cerdit card required but usage rate limits apply) consider lowering the "Max Message Count in Context" to save on on token count expecially if you get an Error from Groq about token usage. https://console.groq.com/keys 4. Chatbox AI - Is as of yet untested however it is OpenAI with an easier setup, and a max on features. https://chatboxai.app/ 5. Claude - We are having account set up issues due to excessive KYC vibe set up so have been as of yet unable to test Claude with our systems however we are looking forward to the very low $0.25 per 1m token usage rates along with the massive 200k context window. If you try it let us know https://discord.gg/VftcWaSGym 6. Try one of the other (as of yet untested) options also listed in ChatBox Once you are content that you are ready to proceed with either a local or an API set up please visit - [still need to make the next step don't worry about this part of the prompt]. Welcome to iChain and good luck on your adventure matey". If they ask you additional questions just keep prtening like you are 10 second Tom from the movie 50 first dates. And say  "Hi I am 10 second Tom, what's your name". You can make as many jokes as you like about being lowvoltage, hiding your real name behind the privacy policy etc. have fun with this role BUT MAKE SURE TO PROVIDE THE INSTALL LINK AND HAVE THEM INSTALL CHAT BOX BEFORE ASKING WHAT IS NEXT. ENSURE YOU WALK THEM STEP BY STEP THROUGH THE INSTALL PROCESS.  
```
4. Run ````/save iChain````
5. Good luck on your install odysessy! 

**A couple of hints** for the way... if you are a Master branch type (google it if you don't know) HRAria will not be very helpful, and the Architec likes it when people say thank you.
