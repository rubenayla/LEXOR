## Phoneme-to-Character Mapping
| **Phoneme** | **IPA Symbol** | **Proposed Character** | **Type**    | **Articulation/Description**          | **Origin/Notes**        |
|-------------|----------------|-------------------------|-------------|----------------------------------------|--------------------------|
| a           | /a/            | `a`                   | Vowel       | Open front unrounded vowel             | Standard vowel           |
| e           | /e/            | `e`                   | Vowel       | Close-mid front unrounded vowel        | Standard vowel           |
| i           | /i/            | `i`                   | Vowel       | Close front unrounded vowel            | Standard vowel           |
| o           | /o/            | `o`                   | Vowel       | Close-mid back rounded vowel           | Standard vowel           |
| u           | /u/            | `u`                   | Vowel       | Close back rounded vowel               | Standard vowel           |
| æ           | /æ/            | `c`                   | Vowel       | Near-open front unrounded vowel        | Distinct vowel sound     |
| y           | y              | `y`                   | Vowel       | Open-mid back unrounded vowel          | Open-mid back unrounded vowel. |
| x           | /ʃ/            | `x`                   | Consonant   | Voiceless postalveolar fricative (sh)  | Chosen for the `sh` sound |
| ch          | /t͡ʃ/          | ch                    | affricate   | Voiceless postalveolar affricate (ch)  | As in Spanish "chico"    |
| p           | /p/            | `p`                   | Consonant   | Voiceless bilabial plosive             | Plosive                  |
| t           | /t/            | `t`                   | Consonant   | Voiceless alveolar plosive             | Plosive                  |
| k           | /k/            | `k`                   | Consonant   | Voiceless velar plosive                | Plosive                  |
| b           | /b/            | `b`                   | Consonant   | Voiced bilabial plosive                | Plosive                  |
| d           | /d/            | `d`                   | Consonant   | Voiced alveolar plosive                | Plosive                  |
| g           | /g/            | `g`                   | Consonant   | Voiced velar plosive                   | Plosive                  |
| j           | /x/            | `j`                   | Consonant   | Voiceless velar fricative (Spanish j)  | As in Spanish "j" / German "Bach" |
| f           | /f/            | `f`                   | Consonant   | Voiceless labiodental fricative        | Fricative                |
| s           | /s/            | `s`                   | Consonant   | Voiceless alveolar fricative           | Fricative                |
| v           | /v/            | `v`                   | Consonant   | Voiced labiodental fricative           | Fricative                |
| z           | /z/            | `z`                   | Consonant   | Voiced alveolar fricative              | Fricative                |
| l           | /l/            | `l`                   | Consonant   | Alveolar lateral approximant           | Lateral                  |
| m           | /m/            | `m`                   | Consonant   | Bilabial nasal                         | Nasal                    |
| n           | /n/            | `n`                   | Consonant   | Alveolar nasal                         | Nasal                    |
| r           | /ɾ/            | `r`                   | Consonant   | Alveolar tap (Spanish single r)        | Rhotic                   |
| h           | /h/            | `h`                   | Consonant   | Voiceless glottal fricative            | Aspirate                 |

- So 24 characters in total. 7 vowels and 17 consonants.
- This means we can generate 17*7*17*7=14161 words in the format of CVCV. That's >50% of the active vocabulary of an average adult English speaker.
- By adding an extra syllable, we can generate $(17*7)^3 = 1\ 685\ 159$ words, which is more than we will ever need.
- Now the work is to make the language consistent. All these words will be easy to pronounce. All connectors and basic common words will be single-syllable words. The most common will be 2-syllable words. Then verbs will be in 'CVC' root + 'V' for conjugation. We have $2023$ possible verbs in this way. People usually use 200 verbs in a daily basis, and recognize about 2000.

### Unused Characters
q, w

### Unused Common Phonemes
- `/ə/` (schwa): as in sofa – Useful for unstressed syllables.
- `/ŋ/` (as in "song") → Velar nasal.
- `/ʒ/` (as in "measure") → Voiced postalveolar fricative.
- `/θ/` (as in "think") → Voiceless dental fricative.
- `/ð/` (as in "this") → Voiced dental fricative.
- `/tʃ/` (as in "chat") → Voiceless postalveolar affricate.
- `/dʒ/` (as in "judge") → Voiced postalveolar affricate.
- `/w/` (as in "we") → Voiced labial-velar glide.
- `/j/` (as in "yes") → Voiced palatal glide.

### Forbidden Phonetics
To ensure clarity and ease of articulation, the following phonetic rules are forbidden:

1. **Words ending with the `k` sound**:
    - Avoid ending words with `k` to reduce abrupt stops in flow.
    - Example: `pak` → Invalid, `pax` → Valid.

2. **Repeated identical consonants**:
    - Avoid sequences like `kk`, `ss`, or `tt`.
    - Example: `katto` → Invalid, `kato` → Valid.

3. **More than two consecutive vowels**:
    - To avoid ambiguity or pronunciation difficulty.
    - Example: `aai` → Invalid, `ai` → Valid.

4. **Combination of `ʃ` (`x`) and `z`**:
    - This creates acoustic overlap; avoid sequences like `xzi`.

5. **Clusters of more than two consonants**:
    - Restrict consonant clusters to a maximum of two consecutive consonants.
    - Example: Valid → `plu`, Invalid → `pltra`.

6. **Vowel following `h`**:
    - Avoid starting a word with `h` directly followed by a vowel to reduce breathy or unclear transitions.
    - Example: `ha` → Invalid, `ha` prefixed with a consonant → Valid (`sha`, `pha`).

7. **Silent Letters**:
    - All characters must represent a distinct phoneme. Silent letters are disallowed to maintain 1-to-1 phoneme-to-character mapping.
    - Example: `knee` → Invalid; `ne` → Valid.

8. **Words starting with `z` and ending with `s` or `x`**:
    - This sequence is phonetically unstable and may cause slurring in rapid speech.
    - Example: `zis`, `zix` → Invalid.
