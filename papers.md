# Monotone Dataflow Framework & Abstract Interpretation
- John B. Kam and Jeffrey D. Ullman. [Monotone Data Flow Analysis Frameworks](https://doi.org/10.1007/BF00290339), Acta Informatica, 7:305-317, 1977.  
- Flemming Nielson, Hanne Riis Nielson, and Chris Hankin. Principles of Program Analysis, 2005, Chapter 4.

# Points-to and Call Graphs
- Olin Shivers. [Control Flow Analysis in Scheme](http://dx.doi.org/10.1145/53990.54007), PLDI '88, pages 167-174.
- Frank Tip, Jens Palsberg. [Scalable Propagation-Based Call Graph Construction Algorithms](http://doi.acm.org/10.1145/353171.353190), OOPSLA '00, pages 281-293.
- Karim Ali, Marianna Rapoport, Ondřej Lhoták, Julian Dolby, and Frank Tip. [Constructing Call Graphs of Scala Programs](http://dx.doi.org/10.1007/978-3-662-44202-9_3), ECOOP '14, pages 54-79.  
- Karim Ali and Ondřej Lhoták. [Averroes: Whole-Program Analysis Without the Whole Program](http://dx.doi.org/10.1007/978-3-642-39038-8_16), ECOOP '13, pages 378-400.
- Ondřej Lhoták and Laurie Hendren. [Scaling Java Points-to Analysis Using Spark](https://doi.org/10.1007/3-540-36579-6_12), CC '03, pages 153-169.

# IFDS & IDE
- Thomas W. Reps, Susan Horwitz, and Shmuel Sagiv. [Precise Interprocedural Dataflow Analysis via Graph Reachability](http://doi.acm.org/10.1145/199448.199462), POPL'95, pages 49-61.
- Shmuel Sagiv, Thomas W. Reps, and Susan Horwitz. [Precise Interprocedural Dataflow Analysis with Applications to Constant Propagation](https://doi.org/10.1016/0304-3975(96)00072-2), Theoretical Computer Science, 167(1-2):131-170, 1996.
- Nomair A. Naeem, Ondřej Lhoták, and Jonathan Rodriguez. [Practical Extensions to the IFDS Algorithm](http://dx.doi.org/10.1007/978-3-642-11970-5_8), CC'10, pages 124-144.
- Johannes Lerch, Johannes Späth, Eric Bodden, Mira Mezini. [Access-Path Abstraction: Scaling Field-Sensitive Data-Flow Analysis with Unbounded Access Paths (T)](http://dx.doi.org/10.1109/ASE.2015.9), ASE '15, pages 619-629.
- Johannes Späth, Lisa Nguyen Quang Do, Karim Ali, Eric Bodden. [Boomerang: Demand-Driven Flow- and Context-Sensitive Pointer Analysis for Java](http://dx.doi.org/10.4230/LIPIcs.ECOOP.2016.22), ECOOP '16, pages 22:1-22:26.
- Johannes Späth, Karim Ali, Eric Bodden. [IDEal: Efficient and Precise Alias-Aware Dataflow Analysis](http://doi.org/10.1145/3133923), OOPSLA '17 (to appear).

# Typestate Analysis
- Nomair A. Naeem and Ondřej Lhoták. [Typestate-like Analysis of Multiple Interacting Objects](http://doi.acm.org/10.1145/1449764.1449792), OOPSLA'08, pages 347-366.
- Xin Zhang, Ravi Mangal, Mayur Naik, and Hongseok Yang. [Hybrid Top-down and Bottom-up Interprocedural Analysis](http://doi.acm.org/10.1145/2594291.2594328), PLDI'14, pages 249-258.

# Analysis Frameworks and Infrastructure
- Martin Bravenboer and Yannis Smaragdakis. Strictly declarative specification of sophisticated points-to analyses, OOPSLA'09, pages 243-262.
- Raja Vallée-Rai, Etienne Gagnon, Laurie J. Hendren, Patrick Lam, Patrice Pominville, and Vijay Sundaresan. Optimizing Java Bytecode Using the Soot Framework: Is It Feasible?, CC'00, pages 18-34.
- Caitlin Sadowski, Jeffrey van Gogh, Ciera Jaspan, Emma Söderberg, and Collin Winter. Tricorder: Building a Program Analysis Ecosystem, ICSE'15, pages 598-608.
- Jens Dietrich, Nicholas Hollingum, and Bernhard Scholz. Giga-Scale Exhaustive Points-To Analysis for Java in Under a Minute, OOPSLA'15.
- Rohan Padhye and Uday P. Khedker. Interprocedural data flow analysis in Soot using value contexts, SOAP'13, pages 31-36.
- Cristiano Calcagno and Dino Distefano. Infer: An automatic program verifier for memory safety of C programs, NFM '11, volume 6617 of LNCS, pages 459–465.

# Android Security
- S. Arzt, S. Rasthofer, C. Fritz, E. Bodden, A. Bartel, J. Klein, Y. L. Traon, D. Octeau, and P. McDaniel. FlowDroid: Precise Context, Flow, Field, Object-sensitive and Lifecycle-aware Taint Analysis for Android Apps, PLDI'14, page 29.
- Damien Octeau, Daniel Luchaup, Matthew Dering, Somesh Jha, and Patrick McDaniel. Composite Constant Propagation: Application to Android Inter-Component Communication Analysis, ICSE'15, pages 77-88.
- Shengqian Yang, Dacong Yan, Haowei Wu, Yan Wang, and Atanas Rountev. Static Control-Flow Analysis of User-Driven Callbacks in Android Applications, ICSE'15, pages 89-99.
- Paolina Centonze, Marco Pistoia, and Omer Tripp. Access-rights Analysis in the Presence of Subjects, ECOOP'15, pages 222-246.
- Lucas Brutschy, Pietro Ferrara, Omer Tripp, and Marco Pistoia. ShamDroid: Gracefully Degrading Functionality in the Presence of Limited Resource Access, OOPSLA'15.
- Pallavi Maiya, Aditya Kanade, and Rupak Majumdar. Race Detection for Android Applications, PLDI'14, page 34.
- Jianjun Huang, Xiangyu Zhang, Lin Tan, Peng Wang, and Bin Liang. AsDroid: Detecting Stealthy Behaviors in Android Applications by User Interface and Program Behavior Contradiction, ICSE'14, pages 1036-1046.
- William Enck, Peter Gilbert, Byung-Gon Chun, Landon P. Cox, Jaeyeon Jung, Patrick McDaniel, and Anmol N. Sheth. TaintDroid: an information-flow tracking system for realtime privacy monitoring on smartphones, OSDI'10 @ USENIX, pages 1-6.

# Analyzing Dynamic Languages
- David Hauzar and Jan Kofroň. Framework for Static Analysis of PHP Applications, ECOOP'15, pages 689-711.
- Koushik Sen, Swaroop Kalasapur, Tasneem G. Brutch, and Simon Gibbs. Jalangi: a selective record-replay and dynamic analysis framework for JavaScript, FSE'13, pages 488-498.
- Magnus Madsen, Frank Tip, and Ondřej Lhoták. Static Analysis of Event-Driven Node.js JavaScript Applications, OOPSLA'15, pages 505-519.
- Essen Andreasen and Anders Møller. Determinacy in Static Analysis for jQuery, OOPSLA'14, pages 17-31.
- Shiyi Wei and Barbara Ryder. Adaptive Context-sensitive Analysis for JavaScript, ECOOP'15, pages 712-734.

# Code Recommender Systems
- Reid Holmes, Gail C. Murphy. Using structural context to recommend source code examples, ICSE '05, pages 117-125.
- Sebastian Proksch, Johannes Lerch, Mira Mezini. Intelligent Code Completion with Bayesian Networks, TOSEM 25(1): 3 (2015).
- Laura Moreno, Gabriele Bavota, Massimiliano Di Penta, Rocco Oliveto, Andrian Marcus. How Can I Use This Method? ICSE (1) 2015, pages 880-890.
- Sebastian Proksch, Sven Amann, Sarah Nadi, Mira Mezini. Evaluating the evaluations of code recommender systems: a reality check. ASE '16, pages 111-121.
- Marcel Bruch, Martin Monperrus, Mira Mezini. Learning from examples to improve code completion systems. FSE '09, pages 213-222.
- Tihomir Gvero, Viktor Kuncak, Ivan Kuraj, Ruzica Piskac. Complete completion using types and weights, PLDI '13, pages 27-38.

# Big Code
- Vaseline Raychev, Martin Vechev, and Andreas Krause. Predicting Program Properties from "Big Code", POPL'15, pages 111-124.
- Veselin Raychev, Pavol Bielik, Martin T. Vechev, Andreas Krause. Learning programs from noisy data, POPL '16, pages 761-774.
- Hitesh Sajnani, Vaibhav Saini, Jeffrey Svajlenko, Chanchal K. Roy, Cristina V. Lopes. SourcererCC: scaling code clone detection to big-code, ICSE '16, pages 1157-1168.

# Usability of Static Analysis Tools
- Brittany Johnson, Yoonki Song, Emerson R. Murphy-Hill, and Robert W. Bowdidge. Why don't software developers use static analysis tools to find bugs?, ICSE'13, pages 672-681.
- Justin Smith, Brittany Johnson, Emerson Murphy-Hill, Bill Chu and Heather Richter Lipford. Questions Developers Ask While Diagnosing Potential Security Vulnerabilities with Static Analysis, FSE'15, pages 248-259.
- Jim Witschey, Olga Zielinska, Allaire Welk, Emerson Murphy-Hill, Chris Mayhorn, and Thomas Zimmermann. Quantifying developers' adoption of security tools, FSE'15, pages 260-271.
- Maria Christakis and Christian Bird. What Developers Want and Need from Program Analysis: An Empirical Study, ASE'16, pages 332-343.

