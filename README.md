# CSC3031Coursework
Newcastle University - 2021/22 - 3rd Year

	RESEARCH AND PROJECT SKILLS MODULE
	
	Preperation for final year project and dissertation
	
	Recorded Video and Oral Presentation Submitted: 25/02/2022
	Peer Review Submitted: N/A
	Ethics Form Submitted: 02/03/2022
	Project Proposal Submitted: 11/03/2022

Marks and Feedback

	RECORDED VIDEO AND ORAL PRESENTATION
	
	Marks: 9/10
	Feedback: 
		The student stayed within the 10 minutes limit (~8mins). The student provides a good contextualization of the most general problem (hardpoint games). Furthermore, graphics were used to describe several points of the slides: state machines, the progress so far, and the agile approach. No typos were found.
	
		Despite the aims are clearly stated, objectives (points 1,2) and methodology (points 3,4) are intermingled. While the former generally refers which are the targets of the evaluations and the projects’ requirements, the latter describe how to meet the former (e.g., implementations, technology used, proposed solutions). Still, the aims and problem’s contextualization is very good, and in might also consider additional risks associated to learning approaches. Still, the student should better specify which kind of AI was exploited: (deep) neural networks, Bayesian models, hidden markov models? E.g., RL might be also considered [4], and a context from real world videogames might be also provided [5]
	
		Some final remarks on the referenced literature. For state machines, you can use better literature from [1] or [2], as they come from appropriate compiler theory literature. Still, the assumption on finite state machines is wrong, as it also possible to learn finite state machines from data [3]! Please re-formulate your content accordingly. Still, “let them learn from themselves” from the Forbes is misleading, as they are not computer scientists: this might force into unsupervised learning while, on the other hand, the majority of machine learning techniques that you are referencing are supervised. Still, the student might also consider the following objectives:
		- Assess the effectiveness of training (tradeoff between training time and accuracy of the trained model)
		- Model’s flexibility (time spent training the algorithm vs. coding a good version of the FSM) and accuracy (Please also considered that FSM can be also learned from the data, and not necessarily hardcoded [3])
	
		[1] Robert M. Keller “Computer Science: Abstraction to Implementation” (2001) https://www.cs.hmc.edu/~keller/cs60book/12%20Finite-State%20Machines.pdf
		[2] A. V. Aho et al. “Compilers: Principles, Techniques, and Tools” (2006) https://www.worldcat.org/title/compilers-principles-techniques-and-tools/oclc/12285707
		[3] S. Agostinelli et al. “Discovering Declarative Process Model Behavior from Event Logs via Model Learning” (2021) https://ieeexplore.ieee.org/document/9576870
		[4] Gino Brunner et al. “Teaching a Machine to Read Maps With Deep Reinforcement Learning“ https://ojs.aaai.org/index.php/AAAI/article/view/11645
		[5] https://montreal.ubisoft.com/en/deep-reinforcement-learning-for-navigation-in-aaa-video-games/
	
		The slides had a readable and consistent style with a good content/view balance. The workup plan was sketched (“Plan of Action”), and the develoipment strategy was also discussed (Agile Framework).
	
		- Dr G Bergami
		
.

	PROJECT PROPOSAL: 
	
	Marks: 66.25/100
	Feedback:
		Motivation:
		The student wrote a nice introduction, where the need of analysing the difference between state machines and AI in videogames, and whether the proposed approach might be able to generate human-like behaviour. Still, the student should discuss why she claims that learning based approches might be better that state machine ones: e.g., flexibility in retraining, do not require hard-coding. Nevertheless, it is also possible to use a learning algorithm to generate a state machine: https://ieeexplore.ieee.org/document/9576870.
		The student should also consider that:
			- Neural Networks are just a model on how a brain might work. Still, our brain does also symbolic reasoning, while current neural network do not natively support that.
			- Still, current AI trained with adversarial training are prone to naive attacks that might hardly trick a human being: https://www.technologyreview.com/2020/02/28/905615/reinforcement-learning-adversarial-attack-gaming-ai-deepmind-alphazero-selfdriving-cars/ therefore, there are some differences.
		These aspects seem to be still waiting to be investigated, as they are reported in the thesis's objectives.
		The student should also motivate how this contribution might advance the state of the art (e.g., such a model comparison related to video-games has not been investigated before).

		Aims and Objectives:
		Despite the student provided a good aim, the objectives contain a mix of very good objectives, as objective measures for assessing the achievement of the most general aim (trade off between training time and accuracy), while some others are more to the methodology required to implement the project (develop a prototype, develop a state AI agent). Still, the student should have considered determining in which way she could consider an AI nearer to a human behavior (e.g., using event traces to compare the behavior to the human to the one generated by the associated state machine or AI?).

		Background:
		The only research-related source provided by the student is a book chapter describing the definition of DFAs/FSMs. Still, most of the literature that the student referenced for the AI/RL/NN part is more of blogs than scientific contributions. Still, the student provided a good source from Ubisoft, thus motivating the feasibility of the recommended approach by pinpointing already-existing solutions for RL in video-games. Furthermore, such a section should not only list a bunch of resources, rather than compare and analyze the pros and cons of each proposed approach.

		Diagrammatic work plan:
		The student provides a Gantt chart which is already broken in subtasks, but where no explicit motivations on such a structure on the light of the tasks’ interdependencies is given. The chart is clearly legible in the digital format. Still, some tasks might be delivered concurrently: when conducting the experiments or when reading the literature, or while logging your activities, you are already writing part of your dissertation, even though at a preliminary stage. So, some tasks might also be described in a better detail.

		Explanation work plan:
		The explanation clearly covers the objectives, identifies some risks that are associated to backup plans. Some interdependencies are also discussed: still, it is not advised to postpone the testing at the end of the project, as it might come towards an integration bloat! As your are following an agile approach, it is better to test each minor release that you are going to provide, so to ensure the correctness and effectiveness of your assumptions/coding task.

		References:
		Despite the student keeps an uniform and standard format for the references, as these completely overlap with the background table, they suffer from the same problems (see above).

		Form:
		The proposal is easy to read, nicely presented, well structured, and no typos were detected. Figures are limited to the diagrammatical plan due to the lack of space. The dissertation adheres with the format specifications.
		
		- Dr G Bergami
