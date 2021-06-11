
**Team IDK
Ananya
Ho Chih Ying
Paul Low
Sydney Teo
Magdeline Ng**

**A short description of the problem we are tackling:**

In a pandemic situation, we can expect more emergency calls. These phone calls could be attributed to genuine health emergencies due to the virus as well as anxious calls from the public who are paranoid and suspect that they have contracted the disease. This can be seen during January to April 2020, where emergency medical service calls increased by 4% from 2019. Moreover, despite SCDF’s efforts to inform the public not to call "995" for non-emergencies, they might still increase due to the increased paranoia pandemics bring with them (Wong, 2021). In 2016, SCDF handled close to 180,000 emergency calls, of which almost 19,000 were false alarms and for non-urgent ailments such as constipation and chronic cough (Wong, 2021).

With SCDF having to respond to non-emergencies, emergencies, as well as pandemic related calls, it is very likely for the current infrastructure and SCDF responders to be overwhelmed by the sheer volume of calls.

Given this situation, it would be crucial to not only distinguish between the types of calls (emergency, non-emergencies and false alarms), but also respond quickly to critical emergencies. We believe this approach can improve the efficiency of SCDF’s emergency call response, hence allowing SCDF to protect and save lives to a larger extent 



**How can technology help?:

Given that we can expect the number of emergency calls to potentially increase in a pandemic, we ought to take steps to ensure that the workflow of emergency medical services calls are optimized and done efficiently so as to better protect and save lives in Singapore. 

Technology is the best way this could be done better. Instead of having a human dispatcher pick up the phone for every single call, perhaps there should be better redistribution of such valuable human resources. Technology through the use of Artificial intelligence and Natural language processing would be crucial in helping us achieve this. This will be explained more in greater detail in our solution descriptions. 

If technology can be well harnessed to classify and prioritize calls, and if artificial intelligence can succeed in processing and interacting with a human during an emergency call, this goes a long way in making SCDF’s call center more efficient. This could help SCDF to protect and save lives as every second would matter in an emergency. 




**The idea our team is proposing:**
SpeedCall, uses a human-like Artificial Intelligence to analyse the call using Natural Language Processing and classify it as an emergency or a non-emergency case. This is done using IBM Watson to make more accurate predictions and further optimize this process. Finally, dispatchers can view necessary information from a single sign-on protected dashboard.

SpeedCall would allow scdf responders to focus on emergencies first. Our AI allows SCDF’s call center to be more robust and sieve out calls that need to be prioritized. This is significant as we should always be prepared for the worst in future pandemic situations. The workflow of emergency medical services calls must be optimized and done efficiently so as to better protect and save lives in Singapore. Moreover, our solution incorporates the use of a natural- sounding contextual AI. This would make our AI more personable and less obvious to the callee. 



**Pitch Video:**
https://youtu.be/-hbmXX6XbTo



**The architecture of our proposed solution:**

![Architecture](https://github.com/MagdelineNg/nlpcode/blob/main/Our%20Solution%20Architecture%20.png)

Firstly, both phone recordings between call bot AI and caller, as well as, important details will be stored into IBM Db2 database as it allows large storage of different types of files. This is done by converting speech to text via Natural Language Processing (NLP).

Furthermore, we will use IBM Watson to help in the classification of emergency and non-emergency cases. This would help to make more accurate predictions in future outcomes and optimize employees' time.

Lastly, SCDF Dispatchers can view necessary information from the dashboard that is protected with IBM Security Verify Access. This simplifies SCDF' access and also provides adequate security to the system as they can log in with federated single sign-on (SSO). 



**Hyperlink to our detailed solution (Long description of our solution):**
https://tinyurl.com/SpeedCallLongSolution



**Getting started (step-by-step instructions to install the required software and how to run a demo of your solution) :**

Utilising SCDF’s years worth of transcripts of emergency and non-emergency calls, the data can be tokenized to obtain the keywords that constantly appear. These keywords, along with data on whether they resulted in an emergency response or a non-emergency response is utilised to form the priority list of keywords, which is then imputed into the IBM Cloud Python code. 

After this, when the transcript of a new call is run through the code, it will be able to determine the priority of emergency of the caller, conduct sentiment analysis as well as language detection and translation. 



**What your team used to build your solution (e.g. IBM Cloud, etc…) :**
Our team used IBM Cloud to build SpeedCall. We made use of various features such as IBM Watson studio, IBM Security verify Access, IBM Database and IBM Cloud object storage.

We also made use of open source Python libraries like nltk, gensim and textblob to perform sentiment analysis and text detection on sample texts.


**credits: https://medium.com/ai4allorg/using-natural-language-processing-to-prioritize-emergency-dispatch-calls-ab830a72de98


