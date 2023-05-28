# Possible lexicographic tasks for LLMs
last updated: 28 May 2023

## Lemma and form tasks
### Headword expansion
* given a list of X words, ask for frequent English words not included in the list

### Forms/run-ons generation
* given a word, ask for words related to that word morphologically
	e.g. if given 'easy' should expect 'easier, easiest, uneasy' etc

### Phrase generation
* given a word, generate a list of frequent phrases or compounds that use that word

## Definition tasks

### Sense expansion
* given a dictionary entry for a word, find senses of that word that are not included in the entry
* given a dictionary entry for a word, find senses for parts of speech not included in the entry

### Definition writing
* given an example or citation, create a definition
	* in a specific format
	* for a specific audience

### Definition rewriting
* given a dictionary definition, rewrite it:
	* into a format suitable for children ages 7-12
	* into Basic English, for learners
	* to be under a certain character count
	* to use words under a certain length
	* to use only a controlled vocabulary 

## Example and citation tasks

### Example creation

* given a dictionary entry for a word, create an example using the word in that sense

### Citation finding
* given a word, find a citation for the word in a published work
	* specify the author (e.g. in Dickens)
	* specify a date (e.g. before 1925)


## Other tasks

### Pronunciation rewriting/writing
* given an IPA pronunciation, rewrite it
	* into a different format (e.g. moo goo gai pan)
	* as it would be pronounced in a different variant (eg British English schedule/shedule)
* given a non-IPA pronunciation, rewrite it into IPA
* given a word, create an IPA pronunciation for it

### Labeling
* given a word, tell me if the word is considered:
	* offensive
	* slang
	* restricted in usage (e.g. 'in Mathematics', 'in the SE US')
	* vulgar
	* archaic
	* obsolete
	* dated
* give me a list of all possibly offensive words between two headwords


### Reverse dictionary/connotation tasks 
* "give me a word that means … " 

### Neologism creation
* "create a word that means X" (using only Latinate forms, etc.) 

### Etymology 
* find the earliest citation for a word

### Usage note creation
* given a word, provide usage guidance

## Illustration
* Given a definition, create a dictionary-style line drawing with labels

