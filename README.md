# \#Irefuse - Action against a significant privacy violation in Belgium and to protect your precious fingerprints.

## tldr;
Step by step details of how to get a new Belgian ID card before April. READ CAREFULLY BEFORE YOU GO!!

## Details
### Intro
Prepare your anus for your ID change rape enforced by the Belgian govrnement with their new, insanly disproportional, fingerprint requirement starting from April 2019. You can fight this measure by requesting a new Belgian ID card BEFORE that. As in every captialist nation you usually vote with your wallet. Belgium is no different here, if you have 25EUR to spare you can get yourself a nice, clean new ID without having to give up your precious fingerprints. I'll detail how and what to expect. That's less than 2 months so plan to get your new ID ASAP. I HIGHLY RECOMMEND READING THIS FULL GUIDE CAREFULLY BEFORE GOING.

### START

In anything you do be POLITE and SUBMISSIVE. Don't get mad or fired up to the bureaucrats (M/X/F), they're a victim of the system just as much as you and just do their job.

_I noted done data, item and financial transactions in some variables in italics_

_TOTAL DATA REQUIREMENT: DATA(PHONE_NUM), DATA(ALT_ID), DATA(ID_LOSS_CASE), DATA(PICTURE), DATA(SIGNATURE)_

_GOV_DATASTORE: A METRIC SHITTON OF DATA._

_GOV_ID_LOSS_COUNTER = YOUR_ID_LOSS_COUNTER_

_INVENTORY: DATA(PHONE_NUM), DATA(SIGNATURE)_

0) Hide your old ID card somewhere in your house. I don't know wether it's a strict requirement but they ask your phone number (_DATA(PHONE_NUM)_) in case something goes wrong with the procedure.

1) Take some alternate form of identification (ALT_ID) with you. E.g. a drivers license, passport, ...
_INVENTORY += ALT_ID, DATA(ALT_ID)_

_INVENTORY = ALT_ID, DATA(ALT_ID), DATA(PHONE_NUM), DATA(SIGNATURE)_

2) Go get some funds at the very least you will need 25EUR but to be sure take some more. I recommend nicely anonymous cash.
_INVENTORY += 25EUR_

_INVENTORY = 25EUR, ALT_ID, DATA(ALT_ID), DATA(PHONE_NUM), DATA(SIGNATURE)_

3) First go get your mugshot (facial picture) taken (cause everyone is a criminal nowadays amiright?) in a photoboot that's compatible with the requirements found below.
Requirements here: https://diplomatie.belgium.be/en/services/services_abroad/belgian_passport/applying_passport/belgian_citizen_belgium/quality
Follow the requirement instructions for the photo carefully or they will make you take a new mugshot!
_INVENTORY -= 5EUR_
_INVENTORY += PICTURE, DATA(PICTURE)_

_INVENTORY = 20EUR, ALT_ID, PICTURE, DATA(ALT_ID), DATA(PICTURE), DATA(PHONE_NUM), DATA(SIGNATURE)_

4) Go to the town hall offices where you live. Take a ticket for the office that handles "Lost ID CARD". DO NOT SAY YOUR ID GOT STOLEN.

_INVENTORY = 20EUR, ALT_ID, PICTURE, DATA(ALT_ID), DATA(PICTURE), DATA(PHONE_NUM), DATA(SIGNATURE)_

5) Wait patiently (this can take a while).

_INVENTORY = 20EUR, ALT_ID, PICTURE, DATA(ALT_ID), DATA(PICTURE), DATA(PHONE_NUM), DATA(SIGNATURE)_

6) If you get called to the office handling your lost ID, explain to the bureaucrat that you lost your old ID card. (NEVER SAY IT WAS STOLEN OR THEY WILL MAKE YOU GO TO THE POLICE FIRST.) ***They might give you a warning that if you lose your ID a third time they will open a case with the police for suspicious activity (I'm not sure if this scare has legal grounds.)*** Just comply with their requests and it will be fine (...I hope). They will possibly also ask your phone number (DATA(PHONE_NUM)).
_INVENTORY -= DATA(PHONE_NUM)_

_GOV_DATASTORE += DATA(PHONE_NUM)_

_GOV_DATASTORE += DATA(ID_LOSS_CASE)_

_GOV_ID_LOSS_COUNTER++_

_INVENTORY = 20EUR, ALT_ID, PICTURE, DATA(ALT_ID), DATA(PICTURE), DATA(SIGNATURE)_

7) Give them your alternative identification (ALT_ID) and mugshot (PICTURE).
_INVENTORY -= ALT_ID, DATA(ALT_ID)_

_INVENTORY -= PICTURE, DATA(PICTURE)_

_GOV_DATASTORE += DATA(ALT_ID), DATA(PICTURE)_

_INVENTORY = 20EUR, DATA(SIGNATURE)_

8) The bureaucrat will do some processing, scan or take your PHOTO and verify your ALT_ID.

***IF THEY ASK YOUR FINGERPRINT AND IT'S NOT YET APRIL 2019 THEY MIGHT BE DOING SOMETHING ILLEGAL. PLEASE CONTACT ME ASAP.***

_INVENTORY = 20EUR, DATA(SIGNATURE)_

9) The bureaucrat will ask you for your signature. Give it to them.
_INVENTORY -= DATA(SIGNATURE)_

_GOV_DATASTORE += DATA(SIGNATURE)_

_INVENTORY = 20EUR_

10) Pay the privacy tax of 20EUR.
_INVENTORY -= 20EUR_

_INVENTORY = 0EUR_

11) The bureaucrat (M/X/F) will give back your alternative identification and a temporary identification document. Do not lose this document because you will need it to receive your new ID card.
_INVENTORY += ALT_ID_

_INVENTORY += TEMP_ID_

_INVENTORY = 0EUR, ALT_ID, TEMP_ID_

9) Wait until you get a letter notice to go get your new ID card. (Couple days or weeks).
_INVENTORY += PUK_PIN_LETTER_


_INVENTORY = 0EUR, PUK_PIN_LETTER, ALT_ID, TEMP_ID_

10) Go back with your temporary identification document and get your brand new, fingerprint absent, ID card. Enter your PUK and PIN to activate your brand new card. 
_INVENTORY -= TEMP_ID_

_INVENTORY -= PUK_PIN_LETTER_

_INVENTORY += NEW_ID_

_INVENTORY = 0EUR, ALT_ID, NEW_ID_

11) Congratz, you now have an id card that's valid for 10 years and have 10 years time to fight this absurd privacy violating measure.
Please share and inform anyone you know to do the same BEFORE APRIL 2019.

#Irefuse, #Ikweiger, #Jerefuse, #Ichweigere
