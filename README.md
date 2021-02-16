Adam Zimmerman  
February 2021

## Multiple Realizability: From Brains to Genes
*Leveraging directed graphs and algebraic topology on neuroscience and genomics! Inspired by philosopher Hilary Putnam.*

#### Introduction

As a master's in biotechnology student with a special interest in novel forms of bioinformatics, I am gearing up for an internship this summer by practicing my Python, math, and genomics skills. The purpose of this and following projects is to wrangle genomic and epigenomic datasets by leveraging algebraic topology and the phenomena that emerge from it, like multiple realizability.

#### Background
At Berkeley in 2011, I studied the philosopher Hilary Putnam and the Philosophy of Mind concept, [*multiple realizability*](https://www.wikiwand.com/en/Multiple_realizability). In order to try to understand it, I drew this asymmetrical diagram:

![phil-of-mind-multiple-realizability-diagram](https://raw.githubusercontent.com/SpaceGold/multiple-realizability/main/multiple-realizability-diagram2.png)

For *b*, imagine distinct neural assemblies, or even different people’s brains. For *p*, imagine different ideas, memes, or, more technically, propositions. These are semiotic units, like meanings or informational bits. Note that each *b* and *p* node is distinct; you may imagine each as *b<sub>1</sub>*, *b<sub>2</sub>*, *p<sub>1</sub>*, etc.

My understanding is that there is an empirically valid asymmetry:
* Physical brain states can entail a common idea
* That idea can entail distinct brain states

But:
* Distinct ideas cannot entail a common brain state
* Nor can a single brain state entail distinct ideas

Therefore, brain states (*b*) are:
* More numerous
* Redundant
* Overlapping
* Constantly changing
* Never identical

In contrast, ideas (*p*):
* Have multiple realizability
* Can be identical
* Can be persistent

For example, the idea that *cats aren't dogs* can be identical between people, but the brain states that hold that thought cannot be identical between people. Plus, even if one person held this thought, their brain states would vary from one moment to the next.

#### Analogies
My 2011 understanding of multiple realizability may have implications for biology, by conceiving of genomics and epigenetics as a high-dimensional [*directed graph*](https://reference.wolfram.com/language/ref/DirectedGraph.html) or network. To get there, I draw these analogies:

Ideas : Brains
: :  
Nature : Nurture  
: :  
Genes : Epigenetics  

#### So what?
The predictive power of these analogies is unclear, but here are some suggestions.  

In the big picture, it should be intuitive now that the environment, be the biosphere, the brain, or the epigenome, is very high in relative complexity. Brains are more complex than thoughts, nurture is more complicated than nature, and epigenetic circumstances are a maelstrom compared to the compressed precision of a genome.

Out of convenience, let's call the left sides of the diagram below the *reactants* sides, where there are inward pointing arrows. Let's call the right sides the *products* sides, where the arrows point outward. Here I paste the same diagram again, but this time with a generalized key that corresponds to epigenetic circumstances (*b*) and genes (*p*):


![generalized-multiple-realizability-diagram](https://raw.githubusercontent.com/SpaceGold/multiple-realizability/main/multiple-realizability-diagram-generalized2.png)


Starting with the product side of the left diagram, we see that a given gene *p* may entail multiple downstream epigenetic states *b*. But the reverse is not true, the right diagram predicts: a given epigenetic circumstance may not result in more than one gene. This is probably because a given epigenetic circumstance is incalculably high in informational complexity, high in dimensions, and therefore idiosyncratic to a single moment in time and a single locus in a specific cell.  

This is confusing, but it might suffice to say that, for example, a UV radiation event could not mutate a cytosine to *both* a guanine *and* an adenine in a given strand of DNA. The reverse is trivially true: a single point mutation may and often will entail multiple dysfunctions downstream.

That covers the products side of each diagram. What about the reactants side, as we might call the inward pointing arrows?

The epigenetic analogy might suggest:  
* Multiple epigenetic circumstances might activate a given gene in a given cell
* But two genes in a given cell will not activate an identical epigenetic circumstance  

This seems about right, doesn't it? What am I missing?

#### Graph Theory and Genomics
Have genomes been characterized in terms of nodes and directional edges, as I depict? Yes.  

Technically what the diagram above depicts are called  [*simplicial complexes*](https://www.youtube.com/watch?v=rlI1KOo1gp4) in [algebraic topology](https://www.wikiwand.com/en/Simplicial_complex). Such complexes are made of *nodes*, like *b* or *p*, and *edges*. When combined, simplicial complexes are called *graphs*, and as detailed with the prose above, these graphs contain additional information when their edges are directional like the arrows above.

#### Next Steps
I aim to predict the prevalence of some rare diseases or specific phenotypic symptoms from genomic marker datasets. Stay tuned for more!
