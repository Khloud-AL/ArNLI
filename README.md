# ArNLI: Arabic Natural Language Inference
Natural Language Inference processes pairs of sentences to extract their semantic relations. 

Pair sentences are annotated with three classes (Contradictions, Entailment, Neutral). Those three classes represent all possible semantic relations between each pair of sentences

**1- Entailment**: A and B intersect (A  ∩ B ≠ ∅, A ∪ B  ≠  Universe) or one may contain another ((A ∁ B) OR (B ∁ A)). Figure 1 represents the Non-Contradiction Algebra Sets with examples.
![](file:///C:/Users/ASUS/Desktop/fig1.png)

**2- Contradiction**: A, B cannot be together, if A is True then B is False (A  ∩ B = ∅, and A ∪ B = Universe). Figure 2 represents the Contradiction Algebra Sets with examples.

![](file:///C:/Users/ASUS/Desktop/fig2.JPG)

**3- Neutral**: A, B have no semantic relations. Each one of them is a different set in universe. No intersection and their union is a subset of universe not all universe (A ∩ B = ∅ and A ∪ B ≠Universe) Figure 3 represents the Neutral Algebra Sets with examples.  

![](file:///C:/Users/ASUS/Desktop/fig3.png)


To the best of our knowledge there is no Arabic dataset designed for contradiction. We created this dataset that contains more than 12k pairs of sentences.
You can get the dataset by contacting us at the email: k-aljallad@aiu.edu.sy
