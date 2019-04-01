# Processing raw data from the Small World of Words

## Context

> The small world of words project is a large-scale scientific study that aims to build a mental dictionary or lexicon 
> in the major languages of the world and make this information widely available.
> 
> In contrast to a thesaurus or dictionary, we use word associations to learn about what words mean and which ones are 
> central in the human mind. This enables psychologists, linguists, neuro-scientists and others to test new theories about 
> how we represent and process language. This knowledge could also be applied in a variety of ways, from learning about 
> the difference between cultures, to learning (or forgetting) new words in a first or a second language.
>
> — Small World of Words  
> — Participate at: <https://smallworldofwords.org/en/project/home>

## Aim

I was given a license waiver to harvest nouns from the SWOW dataset and add them to my public domain list of frequently-used 
common nouns (<http://www.desiquintans.com/nounlist>). Thanks, Simon! If you want access to the data under their existing 
license (CC-BY-NC-ND), you can download it from their website at <https://smallworldofwords.org/en/project/research>.

Simon was kind enough to pull all user responses that were given by at least 2 people, and send them to me as a plain-text 
list. It's a 57,000 line dataset that looks something like this:

```
godson
pike
Nicole kid man
juicy couture
subsume
uncharitable
wake me up before you go go
Independent
```

So I've got my work cut out for me!

## Things to do

[ ] Remove stop words
[ ] Remove/separate phrases
[ ] Tag words with parts-of-speech tags
[ ] Remove proper nouns, acronyms, adverbs, adjectives, stop words, etc. Anything that isn't a common noun.
[ ] Remove slurs >_>
[ ] Lemmatise words to keep only singular forms.
[ ] Word frequency analysis i.e. keep frequently-used nouns only
[ ] Manual vetting of the final noun list
[ ] Merge with Great Noun List
