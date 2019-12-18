# Awesome FHE Research

![Research-FHE](https://github.com/arupmondal-cs/Research-FHE/blob/master/Figure/Research-FHE.png)

This writing was inspired from [awesome](https://github.com/sindresorhus/awesome), [awesome-mpc](https://github.com/arupmondal-cs/awesome-mpc), and [awesome-cryptography](https://github.com/arupmondal-cs/awesome-cryptography) and for our Cryptography research community.

This project designed to have a central place where everyone can find introductory and research materials, as well as open-source software designed for FHE. 

Please feel free to do a pull request with any FHE software or resource you know and it is not on the list. The current classification might not be most suitable one and I am open to any suggestions.

## **```CONTENTS```**

  * [THEORY](#THEORY)
    * [ARTICLES](#ARTICLES)
    * [BOOKS](#BOOKS)
    * [TUTORIALS](#TUTORIALS)
    * [COURSES](COURSES)
    
  * [FHE-TIMELINE](#FHE-TIMELINE)
    * [PRE-FHE](#PRE-FHE-RESEARCH)
    * [FIRST-GENERATION](#FIRST-GENERATION)
    * [SECOND-GENERATION](#SECOND-GENERATION)
    * [THIRD-GENERATION](#THIRD-GENERATION)
    * [SURVEY](#SURVEY)
   
  * [OPEN-SOURCE-SOFTWARE](#OPEN-SOURCE-SOFTWARE)
    * [HElib](#HElib)
    * [SEAL](#SEAL)
    * [PALISADE](#PALISADE)
    * [FHEW/TFHE](#FHEW/TFHE)
    * [HEAAN](#HEAAN)
    * [NFLlib](#NFLlib)
      * [HEAT](#HEAT1)
      * [HEAT](#HEAT2)
    * [cuHE](#cuHE)
    * [SWIFFT](#SWIFFT)
    * [Lol](#Lol)
    * [Lattigo](#Lattigo)


 

## THEORY


## FHE-TIMELINE

In fact, all these different HE attempts can neatly be categorized under three types of schemes with respect to the number of allowed operations on the encrypted data as follows:

 * Partially Homomorphic Encryption (PHE)
 * Somewhat Homomorphic Encryption (SWHE)
 * Fully Homo-morphic Encryption (FHE)

The following [Figure](https://github.com/arupmondal-cs/Research-FHE/blob/master/Figure/HE-TIMELINE.png) shows the Timeline of Homomorphic Encryption(HE) schemes until Gentry’s first Fully-Homomorphic Encryption (FHE) scheme.


![HE Timeline](https://github.com/arupmondal-cs/Research-FHE/blob/master/Figure/HE-TIMELINE.png)

Gentry’s first FHE scheme motivated a large amount of research in the area, mainly with the purpose of improving the efficiency of the original scheme. A Evolution of this research is presented in the following [Figure](https://github.com/arupmondal-cs/Research-FHE/blob/master/Figure/FHE-EVOLUATION.png), with the most relevant references.

 * Ideal lattice based (Ideal)
 * Approximate Greatest Common Divisor (AGCD)
 * Learning With Errors (LWE)
 * Number Theory Research Unit (NTRU)

![FHE EVOL](https://github.com/arupmondal-cs/Research-FHE/blob/master/Figure/FHE-EVOLUATION.png)


## PRE-FHE RESEARCH

 * Ronald Rivest, Leonard Adleman and Mike Dertouzos  
   **_On Data Banks and Privacy Homomorphisms_** [[pdf](http://people.csail.mit.edu/rivest/RivestAdlemanDertouzos-OnDataBanksAndPrivacyHomomorphisms.pdf)]
   
 * Whitfield Diffie, Martin E. Hellman  
    **_New directions in cryptography_** [[pdf](https://ee.stanford.edu/~hellman/publications/24.pdf)]
 
 * Ronald L. Rivest, Adi Shamir, Leonard M. Adleman  
    **_A Method for Obtaining Digital Signatures and Public-Key Cryptosystems_** [[pdf](https://people.csail.mit.edu/rivest/Rsapaper.pdf)]
    
 * Shafi Goldwasser and Silvio Micali  
   **_Probabilistic Encryption_** [[pdf](http://groups.csail.mit.edu/cis/pubs/shafi/1984-jcss.pdf)]
 
 * Taher El Gamal  
   **_A Public-key Cryptosystem and a Signature Scheme based on Discrete Logarithms_** [[pdf](https://link.springer.com/chapter/10.1007/3-540-39568-7_2)]
   
 * Pascal Paillier  
   **_Public-key Cryptosystems based on Composite Degree Residuosity Classes_** [[pdf](https://link.springer.com/chapter/10.1007/3-540-48910-X_16)]
   
 * Ivan Damgard and Mads Jurik
   **_A Generalisation, a Simplification and Some Applications of Paillier's Probabilistic Public-Key System_** [[pdf](http://www.brics.dk/RS/00/45/)]
   
 * Dan Boneh, Eu Jin Goh and Kobbi Nissim  
   **_Evaluating 2-DNF Formulas on Ciphertexts_** [[pdf](http://crypto.stanford.edu/~dabo/abstracts/2dnf.html)]
   

