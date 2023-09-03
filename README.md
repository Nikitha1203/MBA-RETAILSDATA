# MBA-RETAILSDATA
![image](https://github.com/Nikitha1203/MBA-RETAILSDATA/assets/109364397/326075c9-8f60-4223-aecd-0161362a4acd)


Association Rule for Market Basket Analysis
Let I = {I1, I2,…, Im} be an itemset. These itemsets are called antecedents. Let D, the data, be a set of database transactions where each transaction T is a nonempty itemset such that T ⊆ I. Each transaction is associated with an identifier called a TID(or Tid). Let A be a set of items(itemset). T is the Transaction that is said to contain A if A ⊆ T. An Association Rule is an implication of form A ⇒ B, where A ⊂ I, B ⊂ I,  and A ∩B = φ.

The rule A ⇒ B holds in the data set(transactions) D with supports, where ‘s’ is the percentage of transactions in D that contain A ∪ B (i.e., the union of set A and set B, or both A and B). This is taken as the probability, P(A ∪ B). Rule A ⇒ B has confidence c in the transaction set D, where c is the percentage of transactions in D containing A that also contains B. This is taken to be the conditional probability, like P(B|A). That is,

support(A⇒ B) =P(A ∪  B) 
confidence(A⇒ B) =P(B|A)
Rules that satisfy both a minimum support threshold (called min sup) and a minimum confidence threshold (called min conf ) are called “Strong”.

Confidence(A⇒ B) = P(B|A) =
support(A ∪ B) /support(A) =
support count(A ∪ B) / support count(A)
Generally, Association Rule Mining can be viewed in a two-step process:

Find all Frequent itemsets: By definition, each of these itemsets will occur at least as
frequently as a pre-established minimum support count, min sup.
Generate Association Rules from the Frequent itemsets: By definition, these
rules must satisfy minimum support and minimum confidence.
Association Rule Mining
Association Rule Mining is primarily used when you want to identify an association between different items in a set and then find frequent patterns in a transactional database or relational database.


![image](https://github.com/Nikitha1203/MBA-RETAILSDATA/assets/109364397/903c2cb9-b09b-4dfe-bfd6-d58ca0b6178b)

