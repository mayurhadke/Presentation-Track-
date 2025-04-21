# Presentation-Track-
In this repository we (Mayur, Sanket,Tushar, Aryan and Anwarul) are doing the presentation work . 


In today's meet (07 April 2025 ) we sit together and discussed about the presentations and divided sub topics among us. We have already decided the topic i.e. How do credit card transactions work ? before 2 days. 


"Anwarul"(Basically, I will be explain about,

Diffrent types of fees in credit card transactions Assesssment fees, Interchange Fees, Merchant discount rate.
Interchange Fees- It goes to that bank which give you the card.
Assesssment fees- It goes to card network like mastercard, visa etc.
Merchant discount rate- It is paid by shop's to accept your money by credit cards.

How bank and card networks makes money like banks earn by taking intercharge fees, why all cards cost are not same like why credit cards have higher fees than debit cards. Credit cards have more risk also they give us some good offers, cashback and give us some good deals like if we use credit card for flight or train ticket booking we will get exclusive disccount. On other hand deabit card is connected to your money they don't have too much  risk that's why credit card fees are higher than debit cards.

How premium card cost merchants more. 
Premium cards provied us better discount also they have to cover fess like interchange that's why premium card cost merchants more.

How it impact on small businesess- There is a minimum amount purchase setup for cards or any additinal charges for the usage of cards by small businesses.

Then i will  explaining why all of this is important to know how these small costs affect our payment and Why people use diffrent type of payments like cash.

Then,I will use simple examples to explain credit card system function. Suppose if you buy a icecream and pay  ₹100  to shopkeeper by credit card they only get ₹98 rest ₹2 will goes to card and bank network.If he sales 100 icecream in one day then he will be in loos of ₹200.

Dear Anwarul, add the detailed explanation of your topic. Give the explicit information. (comment from Mayur) 


"MD ARYAAN"(Security and Fraud prevention mechanisms)

Subtopics that i'll be covering are:

i)Encryption, tokenization, and CVV/CVC verification: Techniques used to secure sensitive information, how each technique is used and payment security applications.

ii)3D Secure, similar to One-Time Passwords (OTP) verification: an extra layer of security on online transactions. The OTP verification procedure helps in preventing fraudulent transactions.

iii)EMV chip vs. magnetic stripe vs. contactless (NFC) transactions: EVM chip, Magnetic stripe and Contactless transaction(NFC) comparison.

iv)Typical fraud types (card-not-present, phishing, skimming) and countermeasures: Fraud techniques and ways to minimize them.

v)Why it matters: Emphasizes the trust infrastructure for safe use: The effect of security controls and its significance.

1)Securing Your Card Information Online: How Does it Work?

Encryption: Turning Your Information into a Hidden Code

-What it does: Think of encryption as putting your card details into a special scrambler machine. It uses advanced mathematical formulas (algorithms) and a secret 'key' to transform your readable information (like your card number) into unreadable gibberish (ciphertext).

![images](https://github.com/user-attachments/assets/9f7e2d4e-ea30-496f-85e1-bb400444be40)

-Relevance of the problem: In cases where cybercriminals successfully steal your data in transit through the internet, or if they illegally pull it out of an organization's database, they end up getting only a meaningless ciphertext. Without the specific 'key' to decode it, such data is useless to them.

End-to-End Encryption: The data or information is encrypted on the sender's side and can be accessed only by the intended recipient. This activity is highly important, especially for  financial transactions.

![image](https://github.com/user-attachments/assets/7ef85af7-cd98-4808-80ac-c1ea4fe392c1)

Tokenization: Implementing Proxies for Your Confidential Information

-Definition: Rather than constantly giving out your actual card number, tokenization replaces it with a one-of-a-kind, randomly generated placeholder – a 'token'. This token is a placeholder for your actual information, which is stored securely elsewhere.

-Why it matters: If the token is accessed by hackers, it is usually useless to them. It doesn't hold your actual card details, so the threat is much smaller. Most of the systems you utilize (such as digital wallets) are greatly dependent on this.

-Dynamic Tokenization: In some systems, the tokens change often. Hence, even when a hacker steals a token, it will become useless after a few seconds, and so they cannot use it again.

CVV/CVC Validation:

-there are 3 or 4-digit number on the back of the credit or debit card? That is the CVV (Card Verification Value) or CVC (Card Verification Code). When you are entering the card details, it assists in confirming that you actually do possess the card yourself, so it is more difficult for someone who only received the card number to use it illegally.

![image](https://github.com/user-attachments/assets/b825b1a5-6827-4d09-acbc-fc98451aff99)

Dear Aryaan, This is a well-structured and beginner-friendly explanation of key payment security techniques. The use of analogies (like the "scrambler machine") makes complex ideas easy to grasp. (comment by Mayur) 



(Mayur) 
https://youtu.be/cYMeZs_EcqE?si=WtpP1o6sSQzRntqF : Dear All go thorough this video. It will be completely helpful for us. 

\Investigatory questions\ 
1. How Credit card operates ?
2. Who provides the credit card ? 
3. What is the association of credit card provider with the bank ?
4. Purpose of the usage of credit card.
5. Background activity of the credit card when it is swiped ? 
6. Role of interest.
7. What are the types of credit cards ?

\About Credit Card\ 
A credit card is a payment tool issued by banks or financial institutions that allows users to borrow money up to a certain limit to make purchases or pay bills. Unlike debit cards, which use money directly from your bank account, credit cards let you spend first and pay later, usually by the end of a monthly billing cycle. If the full amount isn't paid on time, interest is charged on the remaining balance. Credit cards offer convenience, rewards, and build credit history, but they must be used responsibly to avoid debt.

\Background Process when an individual swipes the card\ 
When an individual swipes (or taps/inserts) a credit card, there’s a whole background process that happens in just a few seconds. Here’s a clear breakdown of what goes on behind the scenes:

🔄 Step-by-Step Background Process of a Credit Card Transaction
1. Card Swiped/Inserted/Tapped
The cardholder gives their card to the merchant or taps it at a terminal.

The terminal reads the card’s information (card number, expiry date, chip data).

2. Authorization Request
The merchant's Point of Sale (POS) machine sends the transaction details (amount, card info) to their Acquiring Bank (the merchant's bank).
The Acquirer forwards this request to the Card Network (Visa, Mastercard, etc.).

3. Communication with Issuer
The Card Network sends the request to the Issuer Bank (the bank that gave the card to the customer).

The Issuer checks:

Is the card valid?

Does the customer have enough credit limit?

Is the transaction suspicious or possibly fraudulent?

4. Authorization Response
The Issuer sends back a response: Approved or Declined.This response goes through the Card Network and Acquirer, back to the POS machine. If approved, the merchant gives the product/service to the customer.

5. Transaction Hold (Temporary)
The approved amount is placed on hold from the customer’s credit limit. It hasn’t been transferred yet—just reserved.

6. Clearing and Settlement (Happens Later)
At the end of the day (or batch time), the merchant sends all transactions to the Acquirer.
The Acquirer sends them through the Card Network to the Issuer.
Settlement happens: Money moves from the Issuer to the Acquirer, and finally to the merchant’s bank account.

💡 Summary:
Swipe → Authorization → Approval → Product given → Later Settlement

This entire process takes 2–4 seconds, even though there are multiple parties involved.
AI Generated Image from ChatGPT :
![ChatGPT Image Apr 8, 2025, 01_15_30 AM](https://github.com/user-attachments/assets/bfd30108-34da-4eea-a465-b5a9b8732e30) 

AI Generated animated video Invideo AI :

"Sanket"

Regulatory and Compliance Framework

I will be coevring the topics which are below.

1. PCI-DSS- Payement Card Industry - Data security Standard

here i will talk about what is PCI-DSS and the dvelopemnt of it, the major contributions of different compeinies in developing it. this is a glbalsecurity standdard which is developed by big brand which manifacture cards such as Visa, and Mastercard.
This Data Security Stanadard is applicable to those who are inckuded in the use of cards for storing data, or proccessing it or transmitting it. traders, and payment proccessors are teh formemost to be included in it.
The Data Security standard PCI-DSS can hold power in follwoing operation:
Secure Network, Protecting cardholders data, Maintaining the system to be non vulnarable for visurses,
Accessing data(Deciding who can acces the data).

2. Role of central Banks and National regulations
e role of Central Bank (Reserve BAnk of India)- regulating card issuing, transaction guidelines, and ssolving the problems related to the use card use.for example to sent the guidelines and to wor on issues relted to card use the central bank came with the concept of tokenization, this proccess turned the cards numbers to digital tokens while tranacting.

3. GDPR and data privacy
GDPR stands for Genral data protection Regulation, it does protect personal data, including financial details used in credit ard transactions. It is enforced by the european union. GDPR ensures some rights to the cardholder- Companies must take consent from user to store user data, users being allowed to see the data of them and purposeof use of Data, users can ask removal of thier data, if data relvant issues happen thenthe authority mus be notified by the companies. e.g. US based companies who store the data of EU cardholder, they must follow GDPR.

4. Regulation of transaction fees and interest rates
the fees structure involves Interchange fees, Assesment fees, merchnat discount rate which is total fees merachnat pays. the EU, RBI, US have thier own structure of fees for the us use cards.




"Tushar"

Future Trends and Challenges in Credit Card Systems

As we know, the credit card industry is a significantly transforming industry that has been experiencing rapid technological advancement. Consumer expectations are one key feature that should be addressed in the future, so I am going to talk about the future trends and challenges in the credit card industry.
As we are heading towards a contactless and digital payment system. The credit card industry is using the NFC(near-field communication) technology is becoming the norm for making in-store transactions due to its high speed and convenience.


However, in today's world, where security is the main concern, credit cards are evolving to be relevant, secure, and trusted by some consumers. As we know, the hacking of our personal information on the internet is a big phenomenon in today’s digital world. The credit card is somewhat of a safe option because fewer stolen cases and a smoother, safer user experience in this mobile and contactless payment world. Mostly developed countries use credit cards for making transactions. 
As the credit card offers an interest-free period(usually 20-50 days), which means you can pay later without extra cost. And also give reward points & cashback, and other discounts for consumers. It also gives purchase protection, insurance, and extended warranty. 
It also has higher spending limits and emergency funds for big purchases. One of the main advantages is that the credit cards are widely accepted globally, which is useful for travel in foreign countries. It also provides the option of buy now and pay later(BNPL), which offers a flexible payment option.

AI use in Credit Card Systems to  minimize the risk


AI and machine learning are revolutionizing credit card fraud detection by analyzing real-time transaction patterns and user behavior, making systems far more effective than traditional rule-based methods. Unlike rigid systems that simply block foreign transactions or large purchases, AI assesses multiple factors—such as spending history, location, purchase timing, and device usage—to distinguish between legitimate and fraudulent activity. 
For example, if a user who typically spends in Mumbai suddenly buys a laptop in Germany, AI checks if they recently booked a flight there instead of outright declining the transaction. It also detects subtle fraud attempts, like micro-transactions used to test stolen cards, and prevents "friendly fraud" by verifying purchase authenticity through device and location data. Additionally, AI stops automated bot attacks by identifying rapid, abnormal transaction patterns. 
By reducing false declines—such as wrongly blocking a hotel booking abroad when the user has a travel history—AI enhances both security and customer experience. Major players like Mastercard, Visa, and leading banks now use AI-driven systems to combat fraud dynamically, ensuring safer transactions while minimizing disruptions for legitimate users.  


Challenges faced by credit cards 



Digital wallets that we use in our daily life to make transactions for commodities such as Apple Pay and Google Pay. This allows user to store multiple payment methods securely to make transactions on their smartphones and other devices such as smartwatches by the use of UPI(Unified Payments Interface). This is one of the big challenges faced by the credit card industry, and also the virtual cards, where we save our card information in our smartphones and use that for buying anything on e-commerce websites. Which is one of the main reasons for the elimination of physical cards is the rising concern towards credit cards. Both are fast, low-cost, and simple for making transactions. If you pay by virtual card, it gets faster than putting your information in again and again. 

Here is the link for ppt-
https://www.canva.com/design/DAGlSJT2zGc/dBEdVt8YDW_3mMfqzVwBLA/edit
we will add more in slides. 




   


