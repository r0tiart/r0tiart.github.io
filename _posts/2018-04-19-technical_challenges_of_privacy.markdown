---
layout: post
title:      "technical challenges of privacy"
date:       2018-04-19 19:04:49 +0000
permalink:  technical_challenges_of_privacy
---


I recently came across this ted talk attached [here](https://www.ted.com/talks/andy_yen_think_your_email_s_private_think_again#t-717242)  it brought up a really interesting topic on our data driven society and the loss of personal privacy. What we think of privacy now a days is screening individuals who can see your profile, but this is just a facade. Your data is virtually public once it goes into the internet. 

The scenario that was described in the ted talk was emails. How we used to send letters - written on a piece of paper, sealed envelope, stamped and addressed - it gets sent to the recipent and only the recipent has the letter. But emails today are postcards - the server / isp is able to see what you wrote and the  email provider sees and stores what you wrote as well. And ofcoure the government can obtain such data when it chooses. The idea that there is privacy in your email is an illusion. 

What they did  bring up on how to solve this issue or start to correct the issue of privacy was an email provider called proton mail. Which creates two encrpytion keys which are linked mathematically, one utilized for public - so someone can encrpyt the email using your public key, which intern can only be opened by the public key providers private key, which is only assoicated with the one individual. 

The idea of encrpytion and security is always an issue when developing an application, but this is primarily password encryption to prevent other indivudals to have access to our accounts. But is that all that is needed? no, sadly our data are publicly available - you can see how things like this transpire with Equifax  where the servers hacked. The data was exposed, but your account on equifax is intact. The idea of encrypting data even if it's just a private message in any popular social media today can be encrpyted using the same methodoly as proton mail. Of course this is me over simplifying and it's probably not how it will actually work, but the idea is to have public and prive keys for each user - and when you are added as a friend you get their private key and things you send are encrypted with it. 

the technical challenges of this is there, but there won't be any wide acceptance until everyone progresses towards the idea of privacy. 
