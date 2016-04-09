# dismathportfolio-kimmaske
dismathportfolio-kimmaske created by Classroom for GitHub

#Dismath Portfolio
#Week 1
<li>We started of with the introduction of <b>Dismath</b> and we had a game starting with the Knight and Knaves. It was a fun game which encompasses the essence of this subject.</li>
<li>I discovered that this subject is purely based on Logic and on how we use our minds to understand the given problems given to us.</li>
<li>This is a challenging subject and I would do my best to pass this subject. </li>

#Week 2
<li>We had a formal introduction to <b>Propositional Logic </b>.</li>
  <b>Proposition</b> is a declarative statement that can either be <b>T(True)</b> or <b>F(False)</b> but not <b>BOTH!</b>.
  <b>Not Proposition</b> is an Imperative or Interrogative statement that is <b>neither</b> True or False.
  <b> Logical Connectives</b> and <b> Logical Operators </b> were also discussed. Shown in the Table below are the different Logical Connectives.
 
| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

  <li>The use of <b> Truth Tables</b> were also introduced to us. It is a method wherein all possible inputs and outputs are listed and established.</li>
  <li>By using the formula 2^n wherein n=number of variables then we would know how many rows are needed for the truth table.</li>
  <li>Truth tables can also help in understanding the different Gates such as the <b> And, Or, Nor, Exclusive Or, Exclusive Nor. </b></li>
#Week 3
<li>The different Identities and Laws were taught to us which is what they call <b>"Logical Equivalences"</b>. It's alsmost the same to the different identities that were taught to us in basic math (eg. Commutative, Identity..) </li>
<li>We can use Truth Tables in proving Equivalences but sometimes it would be harder since it is time consuming and its not that efficient for some items. Hence, the different identites would be helpful since it would prove the equivalence faster and more efficient. </li>
<li>My favourite part of this lecture is the proving part since it really works up your mind and the procedure is not mechanical therefore we really need to think and use our minds.</li>

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
<li><b> Conditional</b> statements were introduced to us and we were given examples to ponder upon.</li>
<li>The Conditional Statement p→q is the proposition "If p then q". It is conditional since it asserts that q is true on the condition that p holds.</li>
<li>Conditional statement is False when P is true and Q is false and true, otherwise.</li>
<li>I've also learned that in a Conditional Statement, <b>P</b> is called the <b>Antecedent,Hypothesis or Premise</b> while <b>Q</b> is called the <b> Conclusion or Consequent </b>.</li>
<li>There are various expressions for a Conditional Statement such as; "if p then q", "p if q", "p is sufficient for q", "p implies q" and many more.</li>

<li><b> Contrapositive, Converse, and Inverse </b> were also discussed.</li>
<li><b> Contrapositive </b> is distinct from the original statement but it is logically equivalent to it.</li>
<li><b> Converse </b> is distinct from the original statement but it is logically independent to it.</li>
<li><b> Inverse</b> is logically distinct but it is not equivalent to the original statement. </li>

<li><b> Compound Propositions </b> were also discussed which are Propositions combined using Logical Operators and Connectives.</li> 
<li>"You can access the internet from Campus only if you know the password".</li>
<li><b>p</b>= "You can access the internet from campus"</li>
<li><b>q</b>="You know the Password"</li>
<li><b>p→q=¬q→¬p</b></li>
<li>This example showed us that every English sentence could be translated into a logical expression.</li>

#Week 5
<li><b>Tautology</b> and <b> Contradictions </b> were also discussed.</li>
<li><b> Tautologies</b> are Compound Propositions that are always True no matter what the truth values of the propositions are.</li> 
     (pv¬p=T)
<li><b>Contradictions</b> are the opposite of Tautologies since it is always False no matter what the truth values of the propositions are.</li>
     (p∧¬p=F)
<li>From Tautology and Contradictions, I have learned that having these in Programs or "Source Codes" means that the program is poorly written.</li>
<li><b>Predicate Logic</b> is also discussed and it deals with predicates and quantifiers. One example of a Predicate Logic:</li>
    "X is greater than 12", X is the subject while "is greater than 12" is the predicate.
<li>There are two types of Quantifiers which is the <b>Universal Quantifier</b> and the <b> Existensial Quantifier</b>.</li>
 <li>  a.) <b> Universal Quantifier (∀x) </b> indicates "for all". This are true unless there is a counter example.</li>
  <li> b.) <b> Existential Quantifier ( ∃x )</b> means "there exists". False unless theres a positive example.</li>
   - The table below shows when a Quantifier is either True or False.
   
   |   Statement   |    When True                         |     
   |:-------------:|:------------------------------------:|
   |    ∀xP(x)     |P(x) is true for every x.             |
   |    ∃xP(x)     |There is an x for which P(x) is True. |
   
   |   Statement   |   When False                          |
   |:-------------:|:-------------------------------------:|
   |    ∀xP(x)     |There is an x for which P(x) is False. |
   |    ∃xP(x)     |P(x) is false for every x.             |
   
   <li><b> Rules of Inference </b> were also discussed.</li>
   <li><b> Arguments</b> are sequence of statements that end with a conclusion.</li>
   <li><b>Validity</b> means conclusion of the final statement of the argument must follow the truth of the preceeding statement.</li>
   <li><b>Fallacies</b> means incorrect reasoning.</li>
   <li>Rules of Inference could be better understood by using this table :</li>
   
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
<b> Method of Proofs </b>
<li> A <b> Proof </b> is a valid argument that establishes the truth of a mathematical statement while a <b> Theorem </b> is a statement that can be proven true.</li>

  <b>A.) Direct Proof</b>
        <li> First step is to assume that P is <b> True</b></li>
        <li>Second Step is to show that Q must also be true .</li>
        
  <b>B.) Proof by Contraposition </b>
         <li>It was discussed that a Contrapositive is distinct to its Original Form but is logically Equivalent to it. 
         -p→q=¬q→¬p</li>
         <li> Proof by Contraposition can be proven by showing that ¬q→¬p is True by taking ¬q as a premise therefore ¬p must follow. </li>
         
  <b>C.) Vacuuos Proof </b>
         <li>Shows that p is false since, p→q mustbe true when p is false.</li>
         
  <b>D.) Trivial Proof </b>
         <li>Shows that q is true, it follows that p→q must be also true.</li>
         
  <b>E.) Proof by Contradiction</b>
        <li>In Proof by Contradiction, we have to assume that ¬p is True since asumming that ¬p is True leads to a contradiction.</li>
        
  <b>F.) Proof by Equivalence (Biconditional)</b>
        <li>To Prove a theorem that is a Biconditional Statement p ↔ q, we must prove that p→q and q→p are both true. </li>
  
<li>These are the basic methods for proving that were discussed. Overall, the only problem that I encountered while learning this was
sometimes I get confused and I don't know what Method to use. I have learned that the best method in proving is to analyze the problem
first. After that then we could try using the basic ones such as Direct Proof and if it wont work then we'd move on to the next method.</li>
        
  
#Week 7


#Week 8
<b> Introduction to Sets and Functions </b>
<li>I have learned that sets are groups of objects that have the same elements or properties </li>
<li>For example, Set of positive integers less than 10 would be {1,2,3,4,5,6,7,8,9}</li>
<li> <b> Elements </b> are the members or objects in a set. </li>
<li> Important Dismath Sets were also discussed such as :</li>
     <li><b>Natural Numbers</b>={0,1,2,3,4,5...}</li>
     <li><b>Integers</b>={.....-3,-2,-1,0,1,2,3....}</li>
     <li><b>Positive Integers</b>={1,2,3,.....}</li>
     <li><b>Rational Numbers</b>={p/q|p∈Z,q∈z,q is not equal to 0}</li>
<li> Sets are Equal if they contain same elements </li>

<li> The use of <b> Ven Diagram </b> is also introduced and it is a graphical method to represent sets </li>
<li> Using a Ven Diagram could also be helpful in getting probabilities of numbers </li>
<li> By using Ven Diagram, we could determine the Union and Intersection of sets</li>

<li><b>Empty Set</b> are sets that doesn't contain any elements and is denoted by {}.</li>
<li><b>Subset</b> are sets that contains the same elements with another set. </li>

<li> Sets also has Identities which could be seen in the table below </li>


|                               Identity                               |        Name         |
|:--------------------------------------------------------------------:|:-------------------:|
|                      A U 0= A <br> A ∩ U= A                          |    Identity laws    |
|                       A U U= U <br> A ∩ 0= 0                         |   Domination laws   |
|                       A U A= A <br> A ∩ A= A                         |   Idempotent laws   |
|                            ¬(¬A) ≡ A                                 | Complementation laws|
|                  A U B= B U A <br> A ∩ B= B ∩ A                      |   Commutative laws  |
|       A U (B U C)=(A U B) U C<br> A ∩ (B ∩ C)= (A ∩ B) ∩ C           |   Associative laws  |
|  A ∩ (B U C)=(A U B) ∩ (A U C)<br> A U (B ∩ C)= (A ∩ B) U (A ∩ C)    |  Distributive laws  |
|              ¬(A U B)=(¬A U ¬B)<br> ¬(A ∩ B)=(¬A ∩ ¬B)               |   De Morgan's laws  |
|                 A U (A ∩ B)=A <br>A ∩ (A U B)= A                     |   Absorption laws   |
|                     A U ¬A= U <br> A ∩ ¬A =0                         |    Negation laws    |

<li> This identities are  similar to the Logical Equivalences discussed </li>
#Week 9
<li> <b> Functions </b></li>
<li> Functions are also called <b>mapping</b> or <b>transformations</b>. It is assigning an Element in Set A to an Element to Set B.</li>  
<li>If f is a function from set A to B. A is the <b> Domain</b> of f while B is the <b>Co-Domain </b> of f. </li>
<li><b>Types of Functions</b></li>
     <li><b> One to One Function(Injective)</b> is a function that assigns elements only once and could never be repeated </li>
     <li><b> Onto Function(Surjective)</b> is a function that contains equal range and domain</li>
     <li><b> One to One Correspondence( Bijective)</b> are functions that are both one to one and onto</li>

<li><b> Floor Functions </b> assigns the largest integer to real number x </li>
<li><b> Ceiling Functions</b> assings the smallest integer to real number x </li>
  
<li><b> Algorithms</b> are sets of instructions for doing a specified task. A person who understands the logic of Algorithms is a good programmer </li>
<li><b> Pseudocodes</b> are type of codes that are intended for human reading. Using Psudocodes before programming helps us understand
the flow of the program better </b>
<li> The different <b> properties</b> of Algorithms are Input, Output, Definitness, Correctness, Finiteness and Generality. </li>

#Week 10
<li><b> Searching Algorithms</b></li>
     <li>Locating an Element in an Ordered List</li>
     
  <li><b> Linear Search Algorithm</b> is when you set the number to 0 first. After that , you compare it to each and every number on the list and if the number is equal to the number being compared then that is the number. Everytime that it is not equal to the desired number then we add 1 to 0 and repeat the steps until we get the desired number </li>
        
  <li><b> Binary Search Algorithm</b>Divide the set of numbers into two and get a middle term. Compare x to the middle term and see if it is greater or less than the middle term. If it is greater than the middle term then choose the upper half, else choose the lower half. Repeat the steps until the desired number is found. </li>
  
  <li><b> Sorting Algorithms</b> is putting unsorted elements in an increasing order. </li>
  
  <li><b> Bubble Sort Algorithm</b> - In this type of algorithm, you compare adjacent elements . If they are in the wrong order then interchange them. Repeat this step until all of the elements in the set are sorted out. </li>
  
  <li><b>Insertion Sort Algorithm</b>- Compare the second element to the first element. If it is less than the first element then place it before the first element. If it is greather than then retain position. Repeat this steps until the elements in the set are sorted out. </li>
  
  <li> <b> Greedy Algorithm </b> selects the best choice or the most optimal solution in a problem rather than following consecutive steps in order to get the desired results as shown wherein Sir Cabatuan showed us the "Problem of making n cents change" problem. </li>
  
#Week 11
<li><b>Growth of Functions</b></li>
<li> It is often represented by <b>Big 0 notation </b>. It is considered as a Big O notation if there are constants c and k such that |f(x)|<= C|g(x)| whenever x>k. The constants c and k are called <b> witnesses</b> </li>.

<li> Big 0 notation does not provide a lower bound for f(x) so that's where <b>Big Omega</b> comes in. 
<li><b> Big Omega Notation</b> is used for the lower bound. </li>
<li><b> Big Theta Notation </b> is used for both upper and lower bound. </li>

<li><b> Algorithm Time Complexity </b> the number of comparisons used would serve as the number of the time complexity. </li>



|                             Complexity                               |        Terminology     |
|:--------------------------------------------------------------------:|:----------------------:|
|                      A U 0= A <br> A ∩ U= A                          |Constant Complexity     |
|                       A U U= U <br> A ∩ 0= 0                         |Logarithmic Complexity  |
|                       A U A= A <br> A ∩ A= A                         |Linear Complexity       |
|                            ¬(¬A) ≡ A                                 |nlogn Complexity        |
|                  A U B= B U A <br> A ∩ B= B ∩ A                      |Polynomial Complexity   |
|       A U (B U C)=(A U B) U C<br> A ∩ (B ∩ C)= (A ∩ B) ∩ C           |Exponential Complexity  |
|  A ∩ (B U C)=(A U B) ∩ (A U C)<br> A U (B ∩ C)= (A ∩ B) U (A ∩ C)    |Factorial Complexity    |

<li> Shown above are the different types of complexities </li>

#Week 12
<b> Graph Theory</b>
<li><b>Graph</b> are structures that is composed of <b>Edges</b> and <b> Vertices(nodes)</b> </li>
<li> It can be applied in a lot of things such as social networking sites like Facebook. </li>

<li>The <b> degree </b> of a vertex in a graph are the number of edges that are incident with it.Having a loop is considered to have twice the degree of the vertex </li>

<li>A vertex of zero degree is called <b> Isolated </b></li>
<li>A <b>Pendant</b> consits of only one degree </li>

<li> <b> Handshaking Theorem </b> states that in an undirected graph, the number of degrees multiplied by the number of vertices is equal to twice the edge. 2e=deg(v), using this formula lets us know the number of edges in a graph </li>
<li>A <b> complete graph</b> denoted by Kn is a type of graph that has one edge between each pair of distinct vertices. Common examples are K33,K5. </li>
<li> <b> Cycles</b> are types of graph wherein the vertices contains only 2 degrees. By putting a vertex in a middle and connecting it to the vertices then we could form a <b> Wheel</b></li>

<li>An <b>Euler Path </b> is a path that travels along every edge exactly once while and <b> Euler Circuit</b> is an Euler Path that begins and ends in the same place </li>
<li>An Euler Circuit has each of the vertices containing an even degree while and Euler Path has exactly two vertices which contains an Odd degree </li>

<li><b> Hamiltonian Path</b> is a path that travels through every vertex in the graph exactly once while a <b> Hamiltonian Path</b>
is a Hamiltonian Path which ends and begins in the same place </li>

<li><b> Adjacency Matrix </b> can also be used in representing a graph. </li>
<li> A graph is <b>Isomorphic</b> if two graphs have different "looks" but are still the same </li>

<li> <b> Planar Graphs </b> are graphs that can be drawn in plane without the edges having to cross </li>
<li> A graph is considered as <b> Homeomorphic Graph </b> it is an elementary subdivision of the original graph </li>
<li>According to <b>Kuratowskis Theorem </b> if a graph is an elementary subdivision of a K33 or a K5 then it is not planar </li>

#Week 13

<b> Graph Coloring </b>
<li> It is the assingment of color to each of the vertices of the graph so that no two adjacent vertices have the same color </li>
<li> The <b> Chromatic </b> number of a graph is the minimum number of colors that would be used in coloring a graph </li>




















































  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
     
