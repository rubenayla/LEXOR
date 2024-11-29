I'm thinking of 

## Phoneme-to-Character Mapping
| **Phoneme** | **IPA Symbol** | **Proposed Character** | **Type**    | **Origin/Notes**        |
|-------------|----------------|-------------------------|-------------|--------------------------|
| a           | /a/            | `a`                   | Vowel       | Standard vowel           |
| e           | /e/            | `e`                   | Vowel       | Standard vowel           |
| i           | /i/            | `i`                   | Vowel       | Standard vowel           |
| o           | /o/            | `o`                   | Vowel       | Standard vowel           |
| u           | /u/            | `u`                   | Vowel       | Standard vowel           |
| æ           | /æ/            | `c`                   | Vowel       | Distinct vowel sound     |
| y           | y              | `y`                   | Vowel       | Open-mid back unrounded vowel. |
| p           | /p/            | `p`                   | Consonant   | Plosive                  |
| t           | /t/            | `t`                   | Consonant   | Plosive                  |
| k           | /k/            | `k`                   | Consonant   | Plosive                  |
| b           | /b/            | `b`                   | Consonant   | Plosive                  |
| d           | /d/            | `d`                   | Consonant   | Plosive                  |
| g           | /g/            | `g`                   | Consonant   | Plosive                  |
| f           | /f/            | `f`                   | Consonant   | Fricative                |
| s           | /s/            | `s`                   | Consonant   | Fricative                |
| v           | /v/            | `v`                   | Consonant   | Fricative                |
| z           | /z/            | `z`                   | Consonant   | Fricative                |
| x           | /ʃ/            | `x`                   | Consonant   | Chosen for the `sh` sound |
| l           | /l/            | `l`                   | Consonant   | Lateral                  |
| m           | /m/            | `m`                   | Consonant   | Nasal                    |
| n           | /n/            | `n`                   | Consonant   | Nasal                    |
| r           | /r/            | `r`                   | Consonant   | Rhotic                   |
| h           | /h/            | `h`                   | Consonant   | Aspirate                 |

### Unused Characters
j, q, w

### Unused Common Phonemes
- /ə/ (schwa): as in sofa – Useful for unstressed syllables.
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
