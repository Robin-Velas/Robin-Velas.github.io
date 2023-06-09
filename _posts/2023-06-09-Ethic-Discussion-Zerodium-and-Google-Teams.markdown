# Discussion on Ethical Issues between Zerodium and Project Zero

Zerodium is an American company specialized in purchasing "zero-day" vulnerabilities from cybersecurity researchers and hackers. It then resells these exploits to clients, including governments and businesses. Unlike traditional bug bounty programs offered by companies, which offer rewards ranging from a few thousand dollars, Zerodium can offer sums of several million dollars for the most critical vulnerabilities. (source :  [1] et [2])

The high resale prices are achievable because Zerodium acts as an intermediary between powerful clients and security researchers seeking financial compensation. By selling these vulnerabilities to state entities and other clients without reporting them to the affected software vendors, Zerodium fuels the black market of exploits that can be used for malicious purposes. If these entities claim to use these vulnerabilities for national security or law enforcement purposes, it also means that a particular exploit is not reported to the responsible company, leaving its clients and users vulnerable to attacks. (source : [3])

It is interesting to note that Zerodium, despite being an American company, originally came from France and is a continuation of a previous company called "Vupen." This company had the same business model of purchasing zero-day exploits, but it was based in France. (source : [4])

In 2015, following the modification of Article 7 of European Directive 2013/40/EU, Vupen transformed into Zerodium and relocated to the United States. Simplified, Europe equated the sale of computer vulnerabilities with the sale of illicit weapons and banned their trade. (source : [5])

During the same period, and almost in response to this emerging market, the Google Project Zero team was created. Its goal is to search for zero-day vulnerabilities in all software used by Google services' users, including those from Microsoft and Apple, so that these companies can fix them before they are exploited by hackers. In their own words, "Our mission is to make it harder for security vulnerabilities to go unnoticed and to significantly improve the safety and security of the Internet for everyone." (source : [6])

Historically, Project Zero was created after the discovery of several critical vulnerabilities, such as "Heartbleed," a major vulnerability in the OpenSSL cryptographic library. However, Project Zero's disclosure policy has been and continues to be criticized. Ninety days after discovering a vulnerability, a detailed article about the flaw is published on the Project Zero blog.

Although 96.1% of vulnerabilities are fixed before this deadline, some vulnerabilities are disclosed without a patch, potentially putting the end-users of the affected software at risk. It is worth noting that this policy is based on the principle that 90 days are sufficient to fix a vulnerability. (source : [8])

An interesting point to raise is the geopolitical consequences caused by the disclosure of such vulnerabilities. In March 2021, the disclosure of 11 zero-day vulnerabilities by Project Zero compromised a counter-terrorism operation that had used these vulnerabilities in its operational process. The country involved is not known, but it is claimed to be a US ally. (source : [9])

We can observe here very different visions regarding the use of zero-day vulnerabilities:

On one side, we have Zerodium, which uses these vulnerabilities as the foundation of its market, acting as an intermediary between security researchers seeking substantial profits and clients chosen by Zerodium who are willing to pay significant sums. Their motivations are not disclosed, and the individuals selling the vulnerabilities to Zerodium cannot choose who they will serve. Moreover, the notion of client selection by Zerodium adds ethical weight to this question, as one may wonder how Zerodium chooses its clients and what the ethical consequences of this practice could be.

Recent revelations about the use of the Pegasus spyware by governments to target journalists, activists, and political opponents have raised ethical questions about zero-day vulnerabilities. Pegasus, developed by the Israeli company NSO Group, is spyware that allows attackers to access all data on a device, including messages, calls, photos, and location information. While NSO Group claims that Pegasus is intended for use by law enforcement and intelligence agencies to combat terrorism and other serious crimes, recent revelations have shown that the spyware has been used abusively by governments to target journalists, human rights activists, and opposition politicians, raising concerns about human rights violations and abuses of power. (source : [10])

The fact that Pegasus exploits zero-day vulnerabilities in mobile operating systems highlights the importance of responsible disclosure and the ethical dilemmas surrounding the sale of such vulnerabilities. By selling zero-day vulnerabilities to governments without informing the relevant software vendors, companies like Zerodium and NSO Group facilitate the creation of tools that can be used for surveillance and censorship.

Another notable example is the use of a zero-day exploit sold by Zerodium. This exploit led to the imprisonment of blogger Ahmed Mansoor, who covered topics related to human rights violations and criticized the government in the United Arab Emirates, for 10 years on charges of "spreading false information to damage the country's image." (source : [11])

On the other side, we have Project Zero, a unit solely dedicated to researching and disclosing zero-day vulnerabilities to improve the overall security of systems used by Google users. A patch deadline is given to companies to avoid full disclosure, thereby creating a danger for users. This is called coordinated disclosure. (source : [12]) However, even with this approach, we can see that it can have serious international consequences, as seen with the failed counter-terrorism operation.

I personally share the perspective of the Project Zero team on cybersecurity. I believe that their way of disclosing vulnerabilities is the most beneficial for a secure digital world. However, I understand the financial incentive that individuals may have to sell their zero-day exploits to platforms like Zerodium. Nevertheless, the consequences can be dramatic, as demonstrated by the Pegasus case. Selling a vulnerability to an unknown organization is, in my opinion, irresponsible and should be illegal. The accumulation of zero-day vulnerabilities in the wild, whether purchased by state actors or not, will inevitably cause harm. We have already witnessed this in 2017 with the leak of NSA's zero-day exploits, which led to the WannaCry ransomware attack. (source : [13])

The ethical issues raised by the sale of zero-day vulnerabilities are complex, and it is important to continue debating these questions to determine best practices for protecting users and avoiding abuses of power.

[1]: https://zerodium.com/

[2]: https://en.wikipedia.org/wiki/Zerodium

[3]: https://cybernews.com/editorial/governments-pay-millions-for-0days-more-harm-than-good/

[4]: https://www.challenges.fr/high-tech/piratage-zerodium-la-discrete-place-de-trading-des-failles-informatiques-fondee-par-un-francais_775028

[5]: https://www.orangecyberdefense.com/fr/insights/blog/gestion-des-vulnerabilites/zero-day-3-3-un-marche-lucratif

[6]: https://googleprojectzero.blogspot.com/p/about-project-zero.html

[7]: https://www.cyberuniversity.com/post/quest-ce-que-la-vulnerabilite-heartbleed-comment-fonctionne-t-il-et-comment-a-t-il-ete-corrige

[8]: https://googleprojectzero.blogspot.com/p/vulnerability-disclosure-faq.html

[9]: https://www.technologyreview.com/2021/03/26/1021318/google-security-shut-down-counter-terrorist-us-ally/

[10]: https://www.technologyreview.com/2020/08/19/1006458/nso-spyware-controversy-pegasus-human-rights/

[11]: https://rsf.org/en/rsf-unveils-202020-list-press-freedom-s-digital-predators

[12]: https://www.techtarget.com/searchsecurity/definition/vulnerability-disclosure

[13]: https://cacm.acm.org/magazines/2021/1/249460-the-ethics-of-zero-day-exploits/abstract
