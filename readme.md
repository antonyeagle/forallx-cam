Forall*x* Adelaide
==================

This is a derivative work created by [Antony Eagle](https://antonyeagle.org), based upon [Tim Button](http://www.homepages.ucl.ac.uk/~uctytbu/index.html)'s 2016 Cambridge version of [PD Magnus](https://www.fecundity.com/job/)'s forall*x* (version 1.29). There are pervasive substantive changes in content, theoretical approach, coverage, and appearance. 

License
-------

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License]("http://creativecommons.org/licenses/by/4.0/).

Source code
-----------

The LaTeX source code for this work is available on GitHub at [github.com/antonyeagle/forallx-adl](https://github.com/antonyeagle/forallx-adl)

Current issues and proposed revisions
-------------------------------------

This text is approaching stability, yet remains under active, albeit intermittent, revision. The current public version of the text is stable for summer term 2020, as it is being used as a textbook in our *Introduction to Logic* course. 

I welcome comments, notification of errors and typos, and any new ideas: [antony.eagle@adelaide.edu.au](mailto:antony.eagle@adelaide.edu.au?subject=forallx-adl). I will update this readme with a list of issues and proposed changes. But I will not push changes until the course is over. 

The following list contains current issues and proposed revisions arranged by chapter:

* Chapter 1 (`forallx-adl-what.tex`) 
* Chapter 2 (`forallx-adl-tfl.tex`)
	- §5
		- 'only if' as 'then'
		- add more remarks on paraphrase – what makes a paraphrase acceptable, ' Since there are important grammatical differences that are argumentatively insignificant, logic will sometimes overlook linguistic accuracy in order to capture the ‘spirit’ of a sentence.'
		- Add a section on modelling and the absence of nuance – how we are attempting to model, not translate. Link forward to later discussion in §8.3.
	- §7
		-  more clarity around quasi-quotation. e.g., if $\mathcal{A}$ is '$A$', $\neg\mathcal{A}$ just is '$\neg A$'. more practice exercises. 	 
* Chapter 3 (`forallx-adl-truthtables.tex`)
	- §8
		+ §8.1: introduce the idea of a function in general.
		+ exercises!
	- §10
		+ Replace 'tautology' by 'logical truth' even for propositional case to ensure consistency with §23; replace 'equivalence' with 'logical equivalence'. 
	- §11
		+ Add a discussion of using the test for entailment to understand NL arguments.
		+ §11.5: two kinds of limits: valid arguments not captured (remedied by \FOL), invalid NL arguments misclassified due to inadequate symbolisation – a form that looks like it might be captured by \TFL\ but which in fact isn't.
	- §13
		+ add discussion of how to handle disjunction, biconditionals in partial truth tables.
		+ Add discussion of how partial truth tables must be constructed with a particular semantic property in mind: that is what determines the starting assumption about truth values that we will make (e.g., using them to assess consistency one begins with `assume all Ts` – but not when using them to assess non-contradictoriness).
* Chapter 4 (`forallx-adl-fol.tex`)
	- §15
		+ practice exercises
		+ discussion of designators (descriptions and singular terms)
		+ pronouns as variables – introduce them as a kind of singular term.
		+ Weather 'it'?
		+ quantifier and matrix
	+ §17
		+ need to explicitly introduce convention that $Axyz$ puts the n-th variable following predicate in the n-th gap.
		+ justify same term in two gaps to account for validity of: 'Amy is self-interested, therefore Amy is interested in someone'.
		+ more on the `with respect to` or `parasitic on` of wider/narrowe scope quantifiers
	- §18
		+ more practice exercises – pure numerical quantification, perhaps from edl textbook or logic manual?
		+ a discussion of how identity, innocuous enough in itself, greatly enriches the expressive power of Quantifier.
	- §19
		- Note that two descriptions can be symbolised with just one existential: 'There is someone who is: a spy and who is the unique spy and who is an escapee and who is the unique escapee'.
		- Perhaps replace §19.3 with a section on whether Russell is offering a model or an analysis – the scope stuff is evidence for the analysis, and then the Strawson-Frege view is the rival (in which the apparent scope effects are treated as whether the proposition about the F or a presupposition that there is a unique F is being rejected).
	- §21
		- domains as needed for extensions.
		- add example of euler with a dot – e.g. willard
	- §22
		- deal with one-place and many-place predicates differently. 
		- use notion of \ntuple explicitly in defs of truth for atomic.
		- add diagrams showing different extended interpretations stemming from a starting interpretation.
		- add 'why don't we do this?' section to quantifier intepretation 	 
	- §23
		- need to expand with examples, and practice problems
		- 
	- §25
		- practice problems
		- mention infinity of intepretations, contrast with sentential case.  	    
* Chapter 5 (`forallx-adl-interpretations.tex`)
* Chapter 6 (`forallx-adl-prooftfl.tex`)
	- §26
		+ Need a practice exercise
		+ add some discussion of epistemology of reasoning – validity is not sufficient for good reasoning, even if it is necessary.
	- §27
		+ add mention that any proof opened with an assumption is already a correct proof.
		+ More on the way that we can use formal proofs to parallel English arguments – the skills are formal, but the motivation is coming up with principles that also govern good arguments in natural language. Indeed, many philosophers write as if they have a natural deduction argument in their head, and their prose just 'de-symbolises' it. Not perhaps the most elegant, but clear, easy to grasp structure, and hopefully good!
	- §28
		+ Mention the first 'rule' which is that we can open an assumption whenever we want. put it alongside Reiteration as a 'connective-insensitive' rule.
	- §29
		+ ramsey quote in conditional intro
	- §31
		- weakening
		- deduction theorem for \vdash
		- entailment (doesn't exist a certain kind of valuation) vs provability (does exist a certain kind of proof)
		- general principle about how we can prove a theorem: must finish a proof with the right kind of rule (bi/conditional intro or ¬ rules) becaue every proof begins with an assumption
		- emphasise relation between easy semantic tasks and tricky proofs, and vice versa  
	- §33
		+ §33.1: mention explicitly that reiteration cannot be used outside a subproof 

* Chapter 7 (`forallx-adl-prooffol.tex`)
	- §35
		+ does the \vdash terminology get re-introduced?
		+ make explicit that the choice of a new name in \exists E is a way of ensuring you meet all the conditions; and make sure that students know choosing a new name is also a way of meeting the conditions on \forall I.
	- §37
	- §38 
		+ some ideas about where next in logic
* Backmatter











