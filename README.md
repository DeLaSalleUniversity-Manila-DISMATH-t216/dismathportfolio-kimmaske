# dismathportfolio-kimmaske
dismathportfolio-kimmaske created by Classroom for GitHub

#Dismath Portfolio
#Week 1
-We started of with the introduction of <b>Dismath</b> and we had a game starting with the Knight and Knaves. It was a fun game which encompasses
the essence of this subject.
- I discovered that this subject is purely based on Logic and on how we use our minds to understand the given problems given to us.
- This is a challenging subject and I would do my best to pass this subject. 

#Week 2
-We had a formal introduction to <b>Propositional Logic </b>.
-<b>Proposition</b> is a declarative statement that can either be <b>T(True)</b> or <b>F(False)</b> but not <b>BOTH!</b>.
-<b>Not Proposition</b> is an Imperative or Interrogative statement that is <b>neither</b> True or False.
-<b> Logical Connectives</b> and <b> Logical Operators </b> were also discussed. Shown in the Table below are the different Logical Connectives.
 
| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

-The use of <b> Truth Tables</b> were also introduced to us. It is a method wherein all possible inputs and outputs are listed and established.
-By using the formula 2^n wherein n=number of variables then we would know how many rows are needed for the truth table.
-Truth tables can also help in understanding the different Gates such as the <b> And, Or, Nor, Exclusive Or, Exclusive Nor. </b>
#Week 3
-The different Identities and Laws were taught to us which is what they call <b>"Logical Equivalences"</b>. It's alsmost the same to the different
identities that were taught to us in basic math (eg. Commutative, Identity..) 
-We can use Truth Tables in proving Equivalences but sometimes it would be harder since it is time consuming and its not that efficient
for some items. Hence, the different identites would be helpful since it would prove the equivalence faster and more efficient. 
- My favourite part of this lecture is the proving part since it really works up your mind and the procedure is not mechanical therefore
we really need to think and use our minds.

|                        Logical   Equivalence                         |        Name         |
|:--------------------------------------------------------------------:|:-------------------:|
|                      p ∧ T ≡ p <br> p v F ≡ p                        |    Identity laws    |
|                       p v T ≡ T <br> p ∧ F ≡ F                       |   Domination laws   |
|                       p v p ≡ p <br> p ∧ p ≡ p                       |   Idempotent laws   |
|                            ¬(¬p) ≡ p                                 | Double negation law |
|                   p v q ≡ q v p <br> p ∧ q ≡ q ∧ p                   |   Commutative laws  |
|       (p v q) v r ≡ p v (q v r) <br> (p ∧ q) ∧ r ≡ p ∧ (q ∧ r)       |   Associative laws  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r) <br>  p ∧(q v r) ≡ (p ∧ q) v (p ∧ r) |  Distributive laws  |
|              ¬(p ∧ q) ≡ ¬p v ¬q <br> ¬(p v q) ≡ ¬p ∧ ¬q              |   De Morgan's laws  |
|                 p v (p ∧ q) ≡ p <br> p ∧ (p v q) ≡ p                 |   Absorption laws   |
|                     p v ¬p ≡ T <br> p ∧ ¬p ≡ F                       |    Negation laws    |



#Week 4
-<b> Conditional</b> statements were introduced to us and we were given examples to ponder upon.
- The Conditional Statement p→q is the proposition "If p then q". It is conditional since it asserts that q is true on the condition that p holds.
-Conditional statement is False when P is true and Q is false and true, otherwise.
-I've also learned that in a Conditional Statement, <b>P</b> is called the <b>Antecedent,Hypothesis or Premise</b> while <b>Q</b> is called 
the <b> Conclusion or Consequent </b>.
-There are various expressions for a Conditional Statement such as; "if p then q", "p if q", "p is sufficient for q", "p implies q" and many more.

-<b> Contrapositive, Converse, and Inverse </b> were also discussed.
-<b> Contrapositive </b> is distinct from the original statement but it is logically equivalent to it.
-<b> Converse </b> is distinct from the original statement but it is logically independent to it.
-<b> Inverse</b> is logically distinct but it is not equivalent to the original statement. 

-<b> Compound Propositions </b> were also discussed which are Propositions combined using Logical Operators and Connectives. 
"You can access the internet from Campus only if you know the password".
<b>p</b>= "You can access the internet from campus"
<b>q</b>="You know the Password"
<b>p→q=¬q→¬p</b>
- This example showed us that every English sentence could be translated into a logical expression.

#Week 5
-<b>Tautology</b> and <b> Contradictions </b> were also discussed.
-<b> Tautologies</b> are Compound Propositions that are always True no matter what the truth values of the propositions are. 
     (pv¬p=T)
-<b>Contradictions</b> are the opposite of Tautologies since it is always False no matter what the truth values of the propositions are.
     (p∧¬p=F)
- From Tautology and Contradictions, I have learned that having these in Programs or "Source Codes" means that the program is poorly written.
-<b>Predicate Logic</b> is also discussed and it deals with predicates and quantifiers. One example of a Predicate Logic:
    "X is greater than 12", X is the subject while "is greater than 12" is the predicate.
- There are two types of Quantifiers which is the <b>Universal Quantifier</b> and the <b> Existensial Quantifier</b>.
   a.) <b> Universal Quantifier (∀x) </b> indicates "for all". This are true unless there is a counter example.
   b.) <b> Existential Quantifier ( ∃x )</b> means "there exists". False unless theres a positive example.
   - The table below shows when a Quantifier is either True or False.
   
   |   Statement   |    When True                         |     
   |:-------------:|:------------------------------------:|
   |    ∀xP(x)     |P(x) is true for every x.             |
   |    ∃xP(x)     |There is an x for which P(x) is True. |
   
   |   Statement   |   When False                          |
   |:-------------:|:-------------------------------------:|
   |    ∀xP(x)     |There is an x for which P(x) is False. |
   |    ∃xP(x)     |P(x) is false for every x.             |
   
   -<b> Rules of Inference </b> were also discussed.
   -<b> Arguments</b> are sequence of statements that end with a conclusion.
   -<b>Validity</b> means conclusion of the final statement of the argument must follow the truth of the preceeding statement.
   -<b>Fallacies</b> means incorrect reasoning.
   -Rules of Inference could be better understood by using this table :
   
   |   Rule of Inference        |            Tautology           |          Name           |
   |:--------------------------:|:------------------------------:|:-----------------------:|
   |       p<br>p→q<br>∴ q      |        (p ∧ (p → q)) → q       |      Modus Ponens       |
   |     ¬q<br>p→q<br>∴ ¬p      |       (¬q ∧ (p → q)) → ¬p      |      Modus Tollens      |
   |     p→q<br>q→r<br>∴ p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism  |
   |      p∨q<br>¬p<br>∴ q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive Syllogism  |
   |       p<br>∴p ∨ q          |           p → (p ∨ q)          |        Addition         |
   |       p ∧ q<br>∴ p         |           (p ∧ q) → p          |      Simplication       |
   |      p<br>q<br>∴ p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction       |
   | p ∨ q<br>¬p ∨ r<br>∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution        | 
   
-One example for rules of Inference:
   " If you have a current password, then you can log onto the network"
     You have a current password
     Therefore,
     You can log onto the network
     
     p→q
     p
     therefore q,   this form of argument is valid since its form is valid.
- I've always thought that a valid form of argument is always valid but I've learned that even though it is a valid form of argument, it 
could also lead to incorrect conclusion.

#Week 6
-<b> Method of Proofs </b>
- A <b> Proof </b> is a valid argument that establishes the truth of a mathematical statement while a <b> Theorem </b> is a statement 
that can be proven true.

  <b>A.) Direct Proof</b>
        - First step is to assume that P is <b> True</b>
        -Second Step is to show that Q must also be true .
        
  <b>B.) Proof by Contraposition </b>
         - It was discussed that a Contrapositive is distinct to its Original Form but is logically Equivalent to it. 
         -p→q=¬q→¬p
         - Proof by Contraposition can be proven by showing that ¬q→¬p is True by taking ¬q as a premise therefore ¬p must follow. 
         
  <b>C.) Vacuuos Proof </b>
         -Shows that p is false since, p→q mustbe true when p is false.
         
  <b>D.) Trivial Proof </b>
         - Shows that q is true, it follows that p→q must be also true.
         
  <b>E.) Proof by Contradiction</b>
        - In Proof by Contradiction, we have to assume that ¬p is True since asumming that ¬p is True leads to a contradiction.
        
  <b>F.) Proof by Equivalence (Biconditional)
        -To Prove a theorem that is a Biconditional Statement p ↔ q, we must prove that p→q and q→p are both true. 
  
  -These are the basic methods for proving that were discussed. Overall, the only problem that I encountered while learning this was
  sometimes I get confused and I don't know what Method to use. I have learned that the best method in proving is to analyze the problem
  first. After that then we could try using the basic ones such as Direct Proof and if it wont work then we'd move on to the next method.
        
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
     
