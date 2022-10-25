Tree-based learning algorithms are a broad and popular family of related nonparametric, supervised methods for both classification and regression. The basis
of tree-based learners is the decision tree wherein a series of decision rules (e.g.,
“If their gender is male…”) are chained. The result looks vaguely like an upsidedown tree, with the first decision rule at the top and subsequent decision rules
spreading out below. In a decision tree, every decision rule occurs at a decision
node, with the rule creating branches leading to new nodes. A branch without a
decision rule at the end is called a leaf.
One reason for the popularity of tree-based models is their interpretability. In
fact, decision trees can literally be drawn out in their complete form (see Recipe
14.3) to create a highly intuitive model. From this basic tree system comes a
wide variety of extensions from random forests to stacking.