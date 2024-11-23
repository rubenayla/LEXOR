[language_roots](./language_roots.md)  
[decisions](./decisions.md)  

# Language
I want an objectively better language from first principles.

The basis will be the set of phonemes and characters, with 1-to-1 mapping. We will build syllables from these, and strive to use all of them in an organized way, so most words are as short as possible.


- Standard placeholder, if you put X repeatedly, understand whether it's the same value being put in several places, or each X is a new different value. Also, symbol when writing, that means it's a placeholder, like brackets etc.
- GPT prompt to help with this: Design a whole language following those guidelines, from the phonetics, to the writing, thinking about the structure of the words, if there are words, verbs etc.

- Stuff - Symbols - Ithkuil, Esperanto
    
    [How to make a language - Part 1 - Biblaridion](https://youtu.be/FHK1gO2Mh68)
    
    ![README/Untitled%2017.png](README/Untitled%2017.png)
    
- What sounds should we use?

- Has to be fast and compact, general for questions but also exact and precise for arguments. Variable precision
- Capability of pronoun-less writing. Something has happened, no need to tell who did it. Most languages express this in a very odd way, it should work better by default.
    - Like this but simple: “Se ha decidido hacer esto”, “It has been decided to do this”
- Has to be able to be written digitally with a few symbols (<64).
- Grouping: Written and talked way to differentiate the levels of nested sentences (The “()” in math, “{}” or tabs in programming). If I say “A and B or C”, you can interpret it as (A&B)|C, in which case C is enough to make the result true, or as A&(B|C) in which case you need both A and some of the others. Maybe this can be achieved tonally by voice and with parentheses in writing, and could be used only when precision is needed. I would not use tone to change the meaning of words.
    - Por ejemplo en español, me pensaba las 3 cosas que pedía calcular se referían al difusor, y no le veía sentido. Tras preguntar a compañeros resulta que el difusor sólo aplica al rendimiento: “Determinar el empuje específico, el impulso específico y el rendimiento isentrópico del difusor”
- Compact words (1 syllable) for
    - Comparators (==, ~=, >=, >, <=, <, !=)
        - Easy for amounts, how to apply to other adjectives? Like “prettier”, but with negative and “less pretty” built-in. One root for all the comparisons.
    - Conditional operators (if, iif, and, or, not, nand, nor, xor).
    - Numbers
        - One syllable per digit
        - Compact way to say negatives
    - Yes, No, True, False, Good, Bad, Directions (Forward, Backward, Left, Right, Up, Down), Ok, Not-sure, Agree, Disagree, Emotions,
- Precise simple way to say directions (in addition to the words for all simple directions)
    - With respect to user, x axis is forward, y left, z up, express rotation angle as a fraction of a turn, that is, “turn 90º left” → “turn sub 3” (dozenal way of 0.25), equivalent to “3 o’clock” angle, but in the opposite direction.
        - 90º → 0;30, 45º → 0;16, 30º → 0;1
- Language should consider talking about sets of things (possible decisions, cases, situations, people, places, etc) more easily. Distinguish between these, and express them easily:
    - Equality:
        - To solve these, consider the set of possible outcomes, and each expression as a selection of which set defines the possible outcomes. If you affirm that something IS x, you selected the outcome. If it IS NOT, anything other than that outcome is true. If it CAN BE, you selected the IS and the uncertainties in between. If it CAN’T BE, you selected the IS NOT.
        - "a = b": affirm that a always equals b, in all cases
        - "a != b": affirm that a never equals b, in all cases
        - "not (a = b)": A does not necessarily have to equal b. This could be interpreted as "a != b" very easily. Should be distinguished in the language.
            - Maybe some other word like "noc a=b" or "a noc = b" (Not in all cases)
        - “[a=b] CAN be true”. Is possible to be true. There is no reason to imply that it can’t be true (possible, likely)
            - “[a=b] DOESN’T HAVE to be true” = can be false, or “There are no reasons to affirm A” without confusing it with A=False
        - “there exists at least one case where [a=b]”
    - Compare amounts (sets A and B)
        - All elements of set A are bigger than all of B
        - There exists at least 1 element in A bigger than B
        - There are no elements in A bigger than B
        - All elements in A are within the bounds of B
        - …
    - “This is false”
        - “This is always false”
        - “There exists at least one case where this is false, even though most of them may be true” (”This” may be a complex statement that changes or depends on the situation)
    - “the probability of [a=b] happening is x”
    - “[a=b] is more likely than [c=d]”
    - a is likely to be [=, $\neq$, or any adjective] to b, 1 syllable
    - Examples:
        - We have masses m1 and m2 → The masses CAN be different. Don’t have to be equal. However the tendency to simplify to “ARE DIFFERENT” is very strong. And that can be wrong in the specific but possible case where m1 = m2. Saying “are generally different” is too dumb and long.
- Others
    - A word to say easily: “I’m in Spain, Madrid, Fuenlabrada, URJC, Building B, at the entrance” without it actually being a list of places. Word with meaning: “and from there, …”, “inside that, …”
- More pronouns for “we”
    - Just you and me
    - You, me, and others
    - Me and others
    - Generic? How to express without needing to specify whether the other person is included. Some questions would include or exclude the person in the set depending on the answer, so it’s annoying.
- Specify existence vs quantity naturally.
    - Example: I have 3 pens. I say “I have 2 pens”. Is that true or false? If I have 3 pens, then I do also have 2. But the total amount is not 2. Does it mean “The amount of pens I have is equal to 3” or “I have 2 pens”, in the sense that “I have them, you don’t know which ones I’m referring to”.
    - language: "Yo voy el sábado", eso quiere decir que, el día que vas es el sábado, o que el sábado irás seguro, aunque vayas otro día antes? Es diferente de decir: "Yo el sábado voy"?
- Distinguish easily the source of the information I’m transmitting.
    - Like in Cherokee language: A suffix is added to the verb, to express whether I saw the info directly or I’ve been told that is the case.
- Express ranges of values, and distributions easily (from 2 to 9, usually about 7). Gaussian distribution with peak at 7 and quartiles or whatever at 2 and 9, one tail much longer than the other. Make it easy to say, since the concept is actually easy.
    - For example: 7 +2-5mm
- Colours: rgb + alpha + matte/shiny (5 dimensions, plain color + 2 dimensions)
- Nope, remove. Best part is no part.
    - Words with no gender. Compact adjectives when needed, but don’t force specificity. Remove he/she difference, use something like “it” by default for objects and people. Then add adjective to specify. If that adjective is always the same for other words, better.
    - “you” plural and singular must be different (Tú ≠ nosotros)
    - No accents
        - In computers: It makes you multiply the amount of characters you need by the amount of accents you have. At least double the characters
        - Hand-writing: It makes you lift the pen, stops the flow of writing.
- Compact way to express the same object in different ways while talking, without needing to express as tangents. Ex: The text (text variable, type string) is added to the PDF (a canvas object)
- When saying x or y, x and y etc and we want to shorten by not including the verb. How to do it?
    - Ex: "You have to write a password with no spaces and |" This means no spaces and no |? I think that should be "with no spaces or |". Are you removing a verb to make it shorter ("and"), or expressing a set of two items that are not allowed? ("or"). This should be more clear, and versatile.

Define words in conversation easily fast. Simplify like when programming, makes it understandable.

Vocabulary with words that include sets of other words elegantly differentiated, with different levels of precision. Easy formation of new words with a system equivalent to prefixes and suffixes. Ex: to upvote, to google, I googled that, earphone, headphone, a redwood... I'm not sure about homonyms, special phrases: to hand something over... I like words that can be used in different ways: a redwood (noun), a redwood tree (adjective)...

Without word gender nor necessity to differentiate singular/plural. Information included in articles or the word itself. Without accents.

All nouns, adjectives, etc with the same ending? At least special sets of words.

Expression for [repeat with more precision, to make clear]:

Example: To make sure you are using the GPU (That is: Get IS CUDA AVAILABLE? = True)
Example phrase: I've heard that they're not going to be able to see each other
- Like Object oriented programming but remember things, like the class etc. For example describing where to click in a complex program gui


## Sounds
| **Group**       | **Sounds**                    | **Summary**                                                                 |
|------------------|-------------------------------|-----------------------------------------------------------------------------|
| **Stop Sounds**  | `p`, `t`, `k`, `b`, `d`, `g` | Sharp, distinct sounds for clear transitions between syllables.             |
| **Fricatives**   | `f`, `s`, `ʃ`, `z`, `v`      | Continuous sounds for modifiable durations, enhancing distinctiveness.      |
| **Affricates**   | `tʃ`, `dʒ`                   | Combination of stop + fricative, adding compact and efficient transitions.  |
| **Nasals**       | `m`, `n`, `ŋ`                | Smooth, resonant sounds that complement the clarity of other groups.        |
| **Vowels**       | `a`, `e`, `i`, `o`, `u`, `æ`, `ɒ` | Distinct vowels covering a wide acoustic range for easy differentiation.    |
| **Consonant Clusters** | `bl`, `tr`, `skr`, `str`     | Dense combinations of consonants, maximizing information per syllable.      |
| **Tonal Variations** | Rising, falling, flat, contour | Adds layers of meaning without increasing syllable length.                  |
| **Optional Clicks** | `ʘ`, `ǀ`, `ǃ`, `ǂ`, `ǁ`    | Distinct non-verbal sounds for extreme environments or unique words.        |

This sound system is designed to maximize efficiency and clarity for a high-bit-rate constructed language. Its **strong points** lie in its **balanced combination of distinct phonemes and tonal variations**. The inclusion of stops, fricatives, and vowels ensures a clear acoustic separation, allowing rapid articulation and reducing the risk of misinterpretation in noisy environments. The dense consonant clusters (e.g., `str`, `skr`) and affricates (`tʃ`, `dʒ`) maximize information density per syllable, enabling compact and meaningful expressions. Tonal variations further enhance the system by encoding additional layers of meaning without increasing syllable length, making it ideal for variable precision in communication. 

The **weaknesses** stem from potential **articulatory complexity and listener fatigue**. While dense clusters and tonal shifts are efficient, they demand precise control over speech production and auditory recognition, which might reduce usability in fast-paced or casual contexts. Nasal sounds and optional clicks help balance this by providing smoother transitions and distinct non-verbal elements, but they might require training for non-native users. 

Overall, this system strikes a **pragmatic balance** between maximizing information transfer and maintaining comprehensibility. It aligns well with the goals of compactness, speed, and clarity while offering flexibility for both general and precise communication. Adjustments may be needed based on cultural preferences or specific environmental requirements for the language's application.

## Core word categories
### Roots

#### Nouns
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `ra`     | thing/object      | Generic item or entity.           |
| `ni`     | place/location    | Physical or conceptual location.  |
| `to`     | person/agent      | Someone or something acting.      |
| `se`     | time/moment       | A point or interval in time.       |
| `na`     | none/nothing      | Absence of an object or concept.  |
| `fu`     | function/purpose  | Purpose or intended use.          |
| `lo`     | logic/truth       | General reasoning or truth.       |

#### Verbs
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `ko`     | move/motion       | Physical or abstract movement.    |
| `vi`     | see/visualize     | Perception or observation.        |
| `po`     | create/make       | Bring something into existence.   |
| `za`     | exist/be          | Indicate existence or state.      |
| `ba`     | start/begin       | Initiate an action or process.    |
| `di`     | finish/end        | Conclude an action or process.    |
| `mo`     | modify/change     | Alter or adjust.                  |
| `su`     | supply/give       | Provide or hand over.             |
| `ta`     | take/receive      | Accept or acquire.                |

#### Modifiers
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `un`     | negate/not        | Reverses or negates meaning.      |
| `tri`    | three/third       | Number 3 or related fractions.    |
| `sub`    | fraction/part     | Denotes a subset or portion.      |
| `wa`     | wide/expand       | To broaden or make larger.        |
| `li`     | limit/restrict    | To constrain or make smaller.     |
| `re`     | repeat/do again   | Indicates repetition.             |
| `ke`     | question          | Inquiry or uncertainty marker.    |

#### Logical and Probabilistic Operators
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `an`     | and               | Logical conjunction.              |
| `or`     | or                | Logical disjunction.              |
| `if`     | conditional       | Dependency or causality.          |
| `prob`   | probably          | Indicates moderate likelihood.    |
| `lik`    | likely            | Indicates high likelihood.        |
| `unlik`  | unlikely          | Indicates low likelihood.         |
| `noc`    | not necessarily   | Ambiguity or partial truth.        |
| `xor`    | exclusive or      | Exactly one condition is true.    |
| `all`    | all (universal)   | Universal quantifier (all cases). |
| `exi`    | exists            | At least one element satisfies.   |

#### Directions
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `x`      | forward           | Movement in the X-axis direction. |
| `y`      | left              | Movement in the Y-axis direction. |
| `z`      | upward            | Movement in the Z-axis direction. |
| `neg`    | backward/down     | Opposite of `x` or `z`.           |

#### States and Affirmations
| **Root** | **Meaning**       | **Notes**                          |
|----------|-------------------|------------------------------------|
| `ye`     | yes               | Affirmation or agreement.         |
| `no`     | no                | Negation or disagreement.         |
| `me`     | maybe             | Neutral or uncertain stance.      |
| `ok`     | acceptable/agree  | Agreement or acknowledgment.      |
| `koe`    | disagree          | Explicit rejection.               |

---

### 2. Reserved Roots for Future Use
| **Reserved Roots** |
|---------------------|
| `be`, `ti`, `ka`, `so`, `nu`, `le`, `pa`, `ku`, `ri`, `da`, `vo`, `ma`, `bo`, `ze` |

## Things to note

### Difference between big and large

### Difference between "a always equals b" and "a can be equal to b" (there exists a possibility in the set of all possibilities where a=b)

### Define the meaning of "a = b" is false. "a = b" is always false for all possibilities, or there exists at least one possibility where a=b is false. Maybe we need two words, or a modifier.


### How to express doubt or uncertainty built-in when thinking about possibilities


# References
- https://github.com/etnms/Conlingua-conlanguage-generator
- https://github.com/arimah/condict