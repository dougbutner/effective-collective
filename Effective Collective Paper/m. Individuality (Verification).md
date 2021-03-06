# Verified Individuality


## Key Points
- We will implement Social Verification for the time being, but acknowledge biometric data may be useful as well. 
- **One individual** (person) per account, enforced through verification
- Every individual resident of Earth can have an account, **no restriction** to gender, nationality, terms with any government or list of individuals
- **Age 12** is the minimum age to open an account 
- **Every individual is given equal ∑**, therefore, equal power
- Every individual has sole control of their own ∑
	- Total control over ∑ in Active account
	- Control of **recipient lists** for passive accounts
- An individual is **not associated with a government ID** 
- An individual is associated with **multi-point biometric data** OR social connections that verify this person is who they say (TBD)
- Account is a **6-digit base-60 ID**, which can be changed any time for a 12∑ fee paid to the Earth Collective's Garden account.


## Verified Individuality Overview
First and foremost, a person's name, government ID, or any other ID should **never be stored** or even asked by the verification system. This ensures each individuals equality in the eyes of Effective. 

Each individual must have **equal collaborative power** and opportunities. There are **no special privileges**, economically or socially, for system founders, wealth holders, etc, outside of the Council of Elders, Project leaders, and Social Leaders.

The only required user-supplied data points are **date of birth,** and **home city** / town. Home city is used to determine which social leaders they are able to support, and where that support goes. This can be changed over time.  

Birth date is needed because each person must be over the age of 12 to get an account. This age is chosen because it is when the brain starts making beta waves, implying the individual can start making critical decisions for their community.

## System Integrity
All of these must be maintained for the integrity of the system
 - One Earthling per account
 - Impossible for another person to change account without true owner's knowledge
 - No government-registered identity information, nor Effective account information should be stored with the biometric data. Any biometric data shouldn't be able to be re-constructed from the stored 

## Biometric VS Social Verification
To prove individuality, two solutions come to the forefront. One is to use biometric data in a way that is client side, provably impossible to reconstruct, and compressed to a point it makes sense to store it on-chain. 

The other option is to use social verification, such done by [brightid](https://www.brightid.org/whitepaper). We will discuss some ideas for each option.

# Case for Biometrics
## Biometric Account Recovery
As the biometric record is only able to check whether or not someone is already on the system, it can be used to recover a wallet by matching an incoming request with an existing account. 

For example, if your wallet holding your Effective is compromised, you would normally lose all of your currency and control of your account. However, with biometric unlocking, you are your recovery phrase.

This would not protect someone from spending all the Effective you have in your account, but it would protect against them gaining control of the account forever, and when you recover the account, you would again receive the Effective daily to build back up your savings. 


## Biometric Challenges
This system must take into account young people that are growing, and who's voice or other biometric information may change considerably by requiring an update periodically. 

Biometric information should hashed in a way that it can never be recreated from the hash, as this will be stored on chain, but can be used to verify a possible match when presented a set of biometric data. In this way, the information can only be used to say "Yes, this is the correct person, or No, this is not the correct person" and check whether a person exists already on the system, as needed to open an account. 


## Biometric Logistics
Creating this biometric system is crucial for the success of Effective, and presents the biggest logistical challenge. Protecting users biometric information in a system without trust is paramount, and requires a hard look at harnessing available algorithms, identifying **minimal representative data points**, and hashing data in **verifiable yet unrecoverable** ways. 

To this end, a sizable amount of the funding received for this project will go towards opening bounties for programmers who can solve these storage problems for several points of biometric data, as well as the corresponding data collection problems implied. 

# Case Against Biometrics
Biometric information is already being abused by governments seeking control and information that facilitates their control and implementation of their policies. To create a system that uses biometric information but does not store reconstructable information is challenging at best. 

Even if a system could meet all requirements, malicious actors may still be able to develop ways to hack phone cameras, etc., to gain access to the specific biometric secrets of users. 

The whole idea of implementing biometric information into this project may also turn people away, particularly the very people that would benefit the most from the system.


# Case for Social Verification
Social verification is low-tech and requires minimal on-chain storage. It also aligns closely with main goal of Effective Collective, which is collaboration. 

Because there are systems already using these approaches, it is possible to hook into these systems, or fork them. Because of this, the tech needed to implement Effective Collective on a global scale already here, and a small amount of effort needed to run the system. 

Benefits like infinitely recoverable accounts may or may not exist depending on the implementations. Private keys are not be generated by social verification data, but using the traditional [ECDSA](https://en.wikipedia.org/wiki/Elliptic_Curve_Digital_Signature_Algorithm?ref=hackernoon.com) method. 


# Case Against Social Verification
To successfully run social verification, trusted representatives must exist to ensure that groups of individuals don't work in malicious ways. This risk of malicious actors can be greatly reduced by these trusted representatives, and by holding users accountable for those they verify. 

Social verification does not stand up to some principles of web 3, including decentralization and provability. While this may present an ideological issue, it's not a real issue as long as the system works.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExNzEzNDQyMDZdfQ==
-->