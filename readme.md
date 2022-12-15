# Movie similarity

Project Description
Natural Language Processing (NLP) is an exciting field of study for data scientists where they develop algorithms that can make sense out of conversational language used by humans. In this Project, you will use NLP to find the degree of similarity between movies based on their plots available on IMDb and Wikipedia.

The dataset contains the titles of the top 100 movies on IMDb as well as each movie's plot summary from both IMDb and Wikipedia.

#Project Tasks

## 1. Import and observe dataset
<p>We all love watching movies! There are some movies we like, some we don't. Most people have a preference for movies of a similar genre. Some of us love watching action movies, while some of us like watching horror. Some of us like watching movies that have ninjas in them, while some of us like watching superheroes.</p>
<p>Movies within a genre often share common base parameters. Consider the following two movies:</p>
<p><img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="2001: A Space Odyssey" src="https://assets.datacamp.com/production/project_648/img/movie1.jpg">
<img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="Close Encounters of the Third Kind" src="https://assets.datacamp.com/production/project_648/img/movie2.jpg"></p>
<p>Both movies, <em>2001: A Space Odyssey</em> and <em>Close Encounters of the Third Kind</em>, are movies based on aliens coming to Earth. I've seen both, and they indeed share many similarities. We could conclude that both of these fall into the same genre of movies based on intuition, but that's no fun in a data science context. In this notebook, we will quantify the similarity of movies based on their plot summaries available on IMDb and Wikipedia, then separate them into groups, also known as clusters. We'll create a dendrogram to represent how closely the movies are related to each other.</p>
<p>Let's start by importing the dataset and observing the data provided.</p>

## 1. Import and observe dataset
<p>We all love watching movies! There are some movies we like, some we don't. Most people have a preference for movies of a similar genre. Some of us love watching action movies, while some of us like watching horror. Some of us like watching movies that have ninjas in them, while some of us like watching superheroes.</p>
<p>Movies within a genre often share common base parameters. Consider the following two movies:</p>
<p><img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="2001: A Space Odyssey" src="https://assets.datacamp.com/production/project_648/img/movie1.jpg">
<img style="margin:5px 20px 5px 1px; height: 250px; display: inline-block;" alt="Close Encounters of the Third Kind" src="https://assets.datacamp.com/production/project_648/img/movie2.jpg"></p>
<p>Both movies, <em>2001: A Space Odyssey</em> and <em>Close Encounters of the Third Kind</em>, are movies based on aliens coming to Earth. I've seen both, and they indeed share many similarities. We could conclude that both of these fall into the same genre of movies based on intuition, but that's no fun in a data science context. In this notebook, we will quantify the similarity of movies based on their plot summaries available on IMDb and Wikipedia, then separate them into groups, also known as clusters. We'll create a dendrogram to represent how closely the movies are related to each other.</p>
<p>Let's start by importing the dataset and observing the data provided.</p>


1. Import and observe dataset
2. Combine Wikipedia and IMDb plot summaries
3. Tokenization
4. Stemming
5. Club together Tokenize & Stem
6. Create TfidfVectorizer
7. Fit transform TfidfVectorizer
8. Import KMeans and create clusters
9. Calculate similarity distance
10. Import Matplotlib, Linkage, and Dendrograms
11. Create merging and plot dendrogram
12. Which movies are most similar?


[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Sidema43/movie-similarity/HEAD)