# Problem-Finder


Jacob, jacob.e.swain@vanderbilt.edu, swainje1, just me


	I believe that there is a very large disconnect between entrepreneurial engineers and knowledge of what problems are actually relevant to people. Very often I’ll hear or read about a project that is technically very advanced and interesting, but just as often, there isn’t a need for what they are making. The project I am working on is aimed at minimizing the discontent between problem solvers and problem havers by collecting, analyzing, and then compiling negative reviews being commonly left on products and services. Ideally, this website would quantitatively rank the largest industry wide problems. Then stakeholders in that industry can then bid on problems they want to be solved, giving problems a bounty of sorts, to incentivize engineers to solve them. If a company or individual contributes towards the “bounty” of a problem then they have rights to use the solution in their products. The bounty is paid to the engineer that solved the problem, with a small fee taken by the website for facilitating the solution. 
	
	From a technical point of view, I plan on using python asynchronous web scraping to collect the negative reviews, api calls to gpt-4 to condense and quantify the reviews, mysql to store the data, and then a python streamlit front end framework to display the results. The first step of making this project would be to build a program that can accurately and efficiently web scrape reviews and store the data collected from them. The next step would be to figure out a way to use a LLM to give quantitative scores to how negative a review is, and to identify the underlying problem in the product that was the cause for that review. Once all reviews can be quantified and labeled, I then would need to write an algorithm that aggregates all negative reviews of the same complaint on the same type of product, and ranks the complaints based on volume and severity of negative reviews.

Goals:
Successfully identify unsolved problems that I was previously unaware of
Have a working prototype of what the website would be
Have the ranking of the problems be significance 
Metrics
The program can run from start to finish (daily update) in under 30 minutes of runtime 
The program can find at least 50 issues and prove a user need for them

