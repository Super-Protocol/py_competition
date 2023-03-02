# [Guide] Super Protocol Python Competition
 
 
![frame1](https://github.com/Super-Protocol/py_competition/blob/782d4fb7f2d66211cc561d74e6d20512d40a8f43/py_compt_cov.jpg)

## Introduction


Our inaugural Super Protocol Python Competition is now live, providing an opportunity for developers to showcase their AI/ML Python solutions built on the Super Protocol Testnet. The competition is designed to demonstrate the readiness of the Super Protocol Testnet infrastructure to deploy simple apps and solutions.

The Competition is designed for skilled indie developers and AI/ML teams proficient in Python, a novice might find it a bit challenging, though we welcome everyone equally. The competition spans two months from registration to the results announcement, giving the developers ample time to create solutions in accordance with the Competition Objectives. These objectives have been chosen based on the most popular and trendy solutions, highlighting the Super Protocol’s ability to tackle modern challenges even during the initial phase of the Testnet.

Participants stand to win 40K TEE Tokens in each Objective category and a grand prize of 10K USDC for the best of the best solution. We invite developers who are keen on exploring the future of Web3 and are competitive enough to participate in the Competition. Register now via the provided link to secure your spot in the competition: [[LINK]](https://superprotocol.typeform.com/pycompetition23)

 

Super Protocol Testnet Phase1 already allows you to deploy your own solutions by using CLI. 

Here is the CLI Video Guide, offering comprehensive instructions on setting up the CLI, creating and managing wallets, as well as interacting with the Super Protocol Testnet:  [[Guide] ⚡️ Super Protocol Testnet Phase1: CLI Scenario](https://youtu.be/xNL4gov99T8) 

### Key takeaways from the guide include:

▪️ The CLI is a command line interface application that enables interaction with the Super Protocol Testnet.

▪️ The guide provides step-by-step instructions for installing the CLI on different operating systems like Mac and Linux.

▪️ Once the CLI is set up, users can create and manage wallets for storing and managing Testnet assets.

▪️ The guide offers guidance on how to create new wallets, view wallet balances, and transfer assets between wallets.

▪️ Additionally, it provides instructions on how to interact with smart contracts on the Super Protocol Testnet, including deployment and calling contract functions.

The guide is well-detailed and includes examples for easy understanding, for more details you can check the [text CLI guide](https://docs.superprotocol.com/testnet/cli/) as well.

It is recommended to check Super Protocol [Whitepaper](https://docs.superprotocol.com/whitepaper/) for a deeper understanding of the infrastructure and the [WebUI guide](https://youtu.be/s61q-LfgEhY) for an easy understanding of the existing solutions

Furthermore, to be eligible to participate in the Python Competition, you will need to request Testnet access via the provided link: https://superprotocol.typeform.com/testnet

## Who is this Competition for?
The Super Protocol Python Competition is tailored for Python developers and developer teams who aspire for complete decentralization in Web3 and are willing to test and contribute to its further development. The only prerequisites for participation are a solid understanding of Python, the ability to take on the challenges, and a passion for Web3.

## The Competition Schedule:


▪️ Registration begins on January 20, 2023 and ends on January 31, 2023. UPD: Registration Extentended until March, 1st, 2023. UPD2: REGISTRATION IS CLOSED!!! But you can still apply on your own risk, since there is only 6 weeks left to the competition final.

▪️ The competition starts on February 1, 2023.

▪️ The challenge will be concluded on April 15, 2023

▪️ Voting starts on April 16, 2023

▪️ Results will be announced on May 1, 2023.

 

## Registration and Contact Information
To register follow this link: [[LINK]](https://superprotocol.typeform.com/pycompetition23)

Fill in the form and wait for confirmation. The process will take no longer than 24 hours. In the interim, feel free to request access to the Testnet if you haven't done so before or if you can’t access previous credentials. Here is the Testnet Request Link: https://superprotocol.typeform.com/testnet


## Competition Objectives
### Objective #1: Best solution in text-to-image AI generation
 

Participants will be provided with **10 phrases, 8 for training the ML algorithm, and 2 for the resulting competition.**

Duration: 2 months [1.5 mo to create a solution and 0.5 mo for results determination]

Results will be facilitated by the Super Protocol Team and winners will be chosen by the Super Protocol community to maintain an independent approach

 

✅ **minimum requirements:**

▪️ **The application should output four generated images for each input phrase.**

▪️  The application should take as input a phrase (dataset), which is located in the file ('INPUT_DIR')/input0001/phrase.txt

▪️  The maximum size for the text file is 512 bytes. Codepage is “utf-8”.

▪️  The application should generate four pictures in jpg format:

('OUTPUT_DIR')/ai.gen01.jpg

('OUTPUT_DIR')/ai.gen02.jpg

('OUTPUT_DIR')/ai.gen03.jpg

('OUTPUT_DIR')/ai.gen04.jpg

**There are environment variables provided:** 

RUN_DIR = os.getenv('RUN_FOLDER') # here are the source texts of the application, incl. - /sp/run

INPUT_DIR = os.getenv('INPUT_DATA_FOLDER') # here is the result of the application - /sp/inputs

OUTPUT_DIR = os.getenv('OUTPUT_DATA_FOLDER') # input here is /sp/output

In addition, we are passing an environment variable PYTHONUSERBASE = "/sp/run/pypi", i.e. external libraries can be put next to the entrypoint.py script in the pypi folder.

The input datasets will be in the form of an offer, with 8 available during development and 2 opened during the final phase.

![Frame1](https://github.com/Super-Protocol/py_competition/blob/782d4fb7f2d66211cc561d74e6d20512d40a8f43/frame1.png)

**Reference**: MidJourney

**Criteria for choosing the best solution:**

▪️  **operation speed**

▪️  **result/request match**

▪️  **Variety of output styles. 4 output pictures should be in 4 different styles (Anime, Van Gogh, Sketch and any other you choose)**

▪️  **style variety**

▪️  see more criteria in **Evaluation and Decision-Making Process for Competition Results section**

✅ Announce the release on the Super Protocol Discord server and make the following tweet:

⚡️ Web3 is coming. Just deployed my own text-2-image AI solution in a fully decentralized and confidential mode thanks to @super__protocol.

👉 Check it out and vote for it here in Discord: https://discord.gg/superprotocol

----

### Objective #2: Best solution in image-to-image AI generation


Participants will be provided with **10 images, 8 for training the ML algorithm, and 2 for the resulting competition.**

**Duration:** 2 months [1.5 mo to create a solution and 0.5 mo for results determination]

Results will be facilitated by Super Protocol Team and winners will be chosen by the Super Protocol community to maintain an independent and transparent approach

 

✅ **minimum requirements:**

▪️ **The application should output four generated images for each input picture, such as converting a photo to anime style or transforming a person from young to old or turning the image into a famous art masterpiece**

▪️ The application should take as input an image (dataset), which is located in the file ('INPUT_DIR')/input0001/image.jpg

▪️ The maximum size for the image is 8 Mb.

▪️ The application should generate four pictures in jpg format:

('OUTPUT_DIR')/ai.gen01.jpg

('OUTPUT_DIR')/ai.gen02.jpg

('OUTPUT_DIR')/ai.gen03.jpg

('OUTPUT_DIR')/ai.gen04.jpg

**There are environment variables provided:** 

RUN_DIR = os.getenv('RUN_FOLDER') # here are the source images of the application, incl. - /sp/run

INPUT_DIR = os.getenv('INPUT_DATA_FOLDER') # here is the result of the application - /sp/inputs

OUTPUT_DIR = os.getenv('OUTPUT_DATA_FOLDER') # input here is /sp/output

In addition, we are passing an environment variable PYTHONUSERBASE = "/sp/run/pypi", i.e. external libraries can be put next to the entrypoint.py script in the pypi folder.

The input datasets will be in the form of an offer, with 8 available during development and 2 opened during the final phase.

**Reference**: Re:Face, Different Dimension Me

**Criteria for choosing the best solution:**

▪️ solution speed

▪️ styles variability

▪️ detalization

▪️ result/request match

▪️ see more criteria in **Evaluation and Decision-Making Process for Competition Results section**

✅ **Announce the release of your solution on the Super Protocol Discord server and make the following tweet:**

⚡️ **Web3 is coming. Just deployed my own image-2-image AI solution in a fully decentralized and confidential mode thanks to @super__protocol**

👉 **Check it out and vote for it here in Discord:** https://discord.gg/superprotocol



## Results Submission
Upon the advent of the submission deadline, developers shall furnish access to the applications in the form of a resource comprising an encrypted file and TII, which will subsequently be utilized to process the order utilizing the mrEnclave feature. It is not necessary to make the code publicly available on platforms such as GitHub or other repositories, as the developer retains the option to keep the code confidential. Following the submission of the work, it is imperative that the developer notify the appropriate parties via the #pythoncompetition channel on the Discord communication platform. It should be noted that this channel is restricted to verified members of the Super Protocol Discord community.

⚠️ It is important to note that the developer retains ownership rights to the submitted solution's code. The primary objective of Super Protocol is to integrate developers into a decentralized confidential cloud ecosystem, providing them with the opportunity to monetize their solutions, rather than acquiring the solutions themselves.

**Important:**

For Competition Objective to be considered valid, it must have at least five competing entries. The objective will not be launched or will be rescheduled until 5 teams have committed. Applications in failed categories can be rescheduled or evaluated outside the program - the jury will consider cases separately

Developer/Team can create no more than one project in each category

As organizers, we reserve the right to remove a team/project/participant from participation without explanation




## Evaluation and Decision-Making Process for Competition Results

Upon notification of the deployment of the solution via the Discord server, a review of the results will be conducted to assess alignment with established criteria prior to eligibility for inclusion in the final evaluation process. A singular private key will be utilized for all orders, facilitating ease of access for all interested parties to verify the legitimacy of the results. The final stages of the competition will be facilitated through the creation of offers on the Super Protocol Testnet, specifically in the form of two data offers (phrase #9 and #10).

The final decision on the 2 winners and the Best solution will be decided by the community's. Voting will start on March 16, 2023 within the Discord community and on Twitter.

Once the final testing phase begins, any changes to the applications will no longer be allowed. Developers will provide access to the applications in the form of a resource to an encrypted file and TII, which will be used to process the order with the mrEnclave feature. The numbers of offers to complete will be provided at a later date closer to the final testing phase.

The results will be announced on April 1st. If you have any questions, feel free to ask our CMs in Discord, cause Pablo, Jami, Cat and Vince are 24/7 available and ready to support you.


### Best solution criteria
 

**Objective’s #1 Best Solution** should match the following criteria: compliance with the guidelines and the objectives, originality of the solution, result/request match, solution speed, style variety, Variety of output styles. 4 output pictures should be in 4 different styles 


**Objective’s #2 Best Solution** should match the following criteria: compliance with the guidelines and the objectives, originality of the solution, result/request match, solution speed, styles variability, detalization

### Important notes

⚠️ External network activity will be unavailable, therefore, third-party solutions cannot be connected
⚠️ 8GB solution size limit
✅ We use Python 3.10 base image 

## Rules and Disqualification
 

Be respectful of other members of the community. This includes refraining from using offensive language or engaging in personal attacks.

Do not cheat or use unauthorized resources during the competition.

Follow the specific rules and guidelines of the competition as outlined here.

Help others in the community when possible, and be willing to ask for help when needed.

Do not engage in any form of plagiarism.

Do not share copyrighted material.

Do not share any personal information of others.

Do not use the community to advertise or promote products or services.

Report any violation of these rules to the Super Protocol community managers

Multiple accounts and duplicate solutions are prohibited. All disputes will be resolved by the Super Protocol Team commission, KYC or a video call may be required to remove the possibility of cheating.

⚠️  Violation of any of these rules will result in disqualification from the competition and a ban from the community.
In disputable situations, it may be necessary to provide the source code, by giving a private key to the container that is on Storj, we may even do it online during video meet to maintain transparency.

### Rewards and Prizes

#### Objective Rewards
Objective #1 – 50,000 TEE [40,000 TEE for the winner, 10,000 TEE reward pool for participation]

Objective #2 – 50,000 TEE [40,000 TEE for the winner, 10,000 TEE reward pool for participation]

Total TEE Reward Pool – 100,000 TEE

⚠️ **Each objective's 10K TEE Reward pool will be divided among all participants, who have successfully deployed a working solution. Only ONE solution in each objective will be awarded with the 40,000 TEE reward. Each objective may have only one best solution as well as only one winner in it.**
⚠️**ALL TEE REWARDS WILL BE DISTRIBUTED ONLY AFTER TGE ACCORDING TO THE REWARD POOL VESTING SCHEDULE**

As for the Best of the Best Solution USDC prize:

1. This reward is exclusively offered to the exemplary solution that surpasses all of the presented alternatives and fulfills all of the competition criteria in a superior manner.

2. There could be no outstanding solutions in this competition, which means that no one will take the grand prize.

3. The Super Protocol Team reserves the right not to award the Grand Prize if they do not find any solutions to be outstanding in the competition.

4. The reward will be distributed within a week after the results are announced.

The rewards are final and set in stone here in this Guide. All the winners will be notified by email with detailed instructions on how to receive their prizes

## [APPLY NOW](https://superprotocol.typeform.com/pycompetition23)

### Useful Links and Guidelines:
 

  Super Protocol Whitepaper: [Whitepaper Status and Updates | Super Protocol](https://docs.superprotocol.com/whitepaper/)

  Super Protocol Testnet CLI guide: [CLI Documentation | Super Protocol](https://docs.superprotocol.com/testnet/cli/)

  Super Protocol Testnet CLI guide: [[Guide] ⚡️ Super Protocol Testnet Phase1: CLI Scenario](https://youtu.be/xNL4gov99T8)

  Super Protocol Discord Community: https://discord.gg/superprotocol



