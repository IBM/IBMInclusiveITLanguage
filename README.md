# IBM Inclusive IT Language
IBM's contribution to open source and other industry efforts to make information technology language more inclusive.

## **Table of contents**

  - [**What IT scope does this initiative cover**](#what-it-scope-does-this-initiative-cover)
  - [**What Terms is IBM replacing**](#what-terms-is-ibm-replacing)
  - [**What areas are you focusing on for inclusion**](#types-of-discriminatory-terms)
  - [**Terminology matters: some Qs and As**](#terminology-matters:-some-Qs-and-As)
      - [**Team Members**](#team-members)
  - [**License**](#license)

## **What IT scope does this initiative cover?**
This initiative covers the following areas of IT: 
* Code used in software and hardware and associated documentation, manuals, support guides, 
* Digital content describing IT products, hardware labels, and education. 

## **What terms is IBM replacing?**

Provided below is the list of terms that have been identified as promoting racial and cultural bias. This list is updated regularly as new guidance is defined.

|Term|Replacement term|More information and rationale|
|----|----|----|
|blacklist|blocklist|As a pair, "blacklist" and "whitelist" promote racial bias by implying that black is bad and white is good. When the terms 'white' or 'black' are used in a context where white is represented as good or black is represented as bad, this usage reinforces a model that promotes racial bias.||25-Jun-20
|whitelist|allowlist||
|slave|Use the appropriate replacement for your domain, such as such as "worker", "child", "helper", "replica", "follower", or "secondary [server, node, process, or other noun]"|The use of the term "slave" in an IT context diminishes the horror of the dehumanizing practice of slavery.|
|master(when paired with slave) |Use the appropriate replacement for your domain, such as "controller", "leader", "manager", "main", "coordinator", "parent", or "primary [server, node, process, or other noun]"|The use of "master" with the term "slave" in an IT context diminishes the dehumanizing practice of slavery. Do not use "master" when a pairing with "slave" is either explicit or implied. Use of the term "master" is acceptable if it is not paired with "slave" and when it is not used to convey power or control over another entity. Context is key. Examples of acceptable uses of "master" include: master data management<br/>master inventor<br/>masters degree|
|master repository|main repository, primary repository|Replace when possible or appropriate. Consider using main repository or primary repository in new products/functions.||9-Nov-20
|black hat hacker|attacker|When the terms 'white' or 'black' are used in a context where white is represented as good or black is represented as bad, this usage reinforces a model that promotes racial bias. The terms "white hat" and "black hat" promote racial bias because black is used to indicate malevolence while white indicates ethical, positive behavior.|
|white hat hacker|offensive security researcher||
|Chinese wall|Use "ethical wall" or "firewall"|This term is outdated and might be perceived as culturally insensitive or offensive because it inappropriately refers to ethnicity.|
|man hour, man day|Use "person hour" and "person day"|These terms use "man" to represent all workers. This is biased language that excludes women.|

## **What areas are you focusing on for inclusion?**
The initial scope of this initiative is IT terminology that promotes racial and cultural bias. We will expand on this scope in the future to address non inclusive IT terms in other areas of diversity.

## **Terminology matters: some Qs and As**
_Language is very powerful. Language does not describe reality. Language creates the reality that it describes._ - Desmond Tutu

### **Can we really bring about change by changing the words we use?**
The language we use signals our intent: our choice of words indicates how we think and feel and it influences the way others perceive things. When we use racially biased terms, it signals support and acceptance of systemic racism. Using neutral or inclusive language frees our content from words that harm and diminish.
Watson Tone Analyzer uses the fields of cognitive and data science to detect the emotional and social tones in written text. These insights are used to drive business decisions in marketing, customer service, and support. The assumption behind this is that the words we use significantly affect the way that our communication is perceived and the effect it has on the people who hear it. Neuroscientists have shown that exposure to negative language releases stress-producing hormones and neurotransmitters in our brains. (see Words Can Change Your Brain by Andrew Newberg, M.D., and Mark Robert Waldman). The words we choose to use have real consequences.
 
### **Isn't prohibiting terms censorship?**
Many large organizations establish and enforce a controlled vocabulary that specifies the terms that everyone should use, as well as identifying terms that are deprecated in that organization. We avoid using terms that can cause legal issues, or problems for accessibility or translation. For example, the terms "upper-left" and "bottom-right" are often prohibited because using these terms makes content difficult or impossible for visually impaired people to use. An idiom like "out of the box" might be prohibited because it is jargon that lacks clarity and is challenging to translate. "Time-tested" might be prohibited because it implies a claim of suitability or reliability that could create a potential marketing or legal problem. 
Using a controlled vocabulary increases the clarity and accuracy of content and enables writers to speak in one voice.

### **How will it make a difference if we change a few words and the rest of the world keeps on using biased terminology?**
We are not alone in making these changes. Many other tech companies are also replacing racially biased terms in their content. Standards organizations like the IEEE are participating to make these replacement terms the standard for the IT industry.
 
### **Why are we taking time away from our actual work to change a few words?**
Communicating effectively and cohesively is expected of all developers and content creators. The words we use must reflect our values and create an environment where everyone can feel included and psychologically safe. In early June 2020, IBM CEO Arvind Krishna asked IBMers to take the Emb(race) pledge, IBM's social justice response for equality and equity. One of the statements in this pledge is "I pledge to demonstrate equality through action." Reinforcing that we use words in IT that are free from racial and cultural bias, is one action that  demonstrates our commitment to equality.
 
### **You can't change our language!**
Language changes constantly. The language of Chaucer and Shakespeare is notably different from the language of today. The meaning of words shifts from century to century and even from decade to decade. The word "meat" used to mean any food. "Nice" once meant foolish while "silly" meant worthy. More recently, words like "sick" and "ghost" have taken on new meanings. Word choices reflect social change as well. The word "mankind" has been gradually falling out of use, and the once-common word "workman" has largely been replaced by "worker".  Our world changes constantly and we change along with it. Language, as the tool we use to express ourselves, has to change along with us in order to serve our needs. 
 
### **How far will this go?**
These changes are being made thoughtfully after consultation with diverse people and subject matter experts. Only those terms that are offensive and perpetuate bias are being addressed.  For example, "master" when used in conjunction with slave has been changed. However, the terms "master inventor", "golden master", and "mastermind" continue to be fine to use. 

### **In IBM, do changes apply to new content and products only or also to existing products and content?**
We issue the following advice:
Before using the terms, assess the impact. As much as possible, stop using the prohibited terms when creating and updating content. However, THINK before you replace terms. Assess the extent to which these terms are used in your product and content, and in what sense they are used. Product documentation should reflect the product that it supports (code, UI, APIs, hardware, etc.). Engage with development and offering management to understand how pervasive it is, and what the impact to clients would be if changes were made to the product. If retrofitting is required, a plan should be created with development and offering management. 
Examples:  
- My product has non-inclusive terminology used in the source code or on product components (e.g., HW cables).  --> Confirm with development if the source code will be changed; if so, coordinate documentation terminology in tandem with the source code changes. If source code will not be changed, do not change the terminology if it will be out of sync with the product that it references.
- My product does not have non-inclusive terminology in source code. -->  Use the new inclusive terms in any content published. If industry standards have not changed, consider adding footnotes for clarity.

### **How is IBM referring to prohibited terms that have not yet been removed from product code and UIs, and/or prohibited terms in technologies that are not owned by IBM?**
We use the following statement in affected content:
-	While IBM values the use of inclusive language, terms that are outside of IBM's direct influence are sometimes required for the sake of maintaining user understanding. As other industry leaders join IBM in embracing the use of inclusive language, IBM will continue to update the documentation to reflect those changes.

## License

This project is licensed under the Apache 2 License - see the LICENSE file for details.