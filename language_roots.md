# Language Phonetics, Rules, and Roots

## 1. Phonetics and Characters

### 1.1 Phoneme-to-Character Mapping

| **Phoneme** | **IPA Symbol** | **Proposed Character** | **Type**    | **Origin/Notes**        |
|-------------|----------------|-------------------------|-------------|--------------------------|
| a           | /a/            | `a`                   | Vowel       | Standard vowel           |
| e           | /e/            | `e`                   | Vowel       | Standard vowel           |
| i           | /i/            | `i`                   | Vowel       | Standard vowel           |
| o           | /o/            | `o`                   | Vowel       | Standard vowel           |
| u           | /u/            | `u`                   | Vowel       | Standard vowel           |
| æ           | /æ/            | `æ`                   | Vowel       | Distinct vowel sound     |
| ɒ           | /ɒ/            | `ɒ`                   | Vowel       | Low back rounded vowel   |
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

- Unused Common Phonemes
    - `/ŋ/` (as in "song") → Velar nasal.
    - `/ʒ/` (as in "measure") → Voiced postalveolar fricative.
    - `/θ/` (as in "think") → Voiceless dental fricative.
    - `/ð/` (as in "this") → Voiced dental fricative.
    - `/tʃ/` (as in "chat") → Voiceless postalveolar affricate.
    - `/dʒ/` (as in "judge") → Voiced postalveolar affricate.
    - `/w/` (as in "we") → Voiced labial-velar glide.
    - `/j/` (as in "yes") → Voiced palatal glide.

- Unused Characters
    - `q`, `c`, `y`, `w`, `j`.

So we have a total of **19** consonants and **7** vowels.
---

## 2. Rules (Phonetic and Grammar, since they match)

### 2.1 Forbidden Phonetics
To ensure clarity, the following phonetic rules are forbidden:
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

### 2.2 Valid Combinations
- **Word Start**: Any consonant or vowel is valid.
- **Word Middle**: Any vowel can follow a consonant; consonant clusters are limited to **two**.
- **Word End**: Must end with a vowel or the following consonants: `p, t, n, l, r`.

Examples:
- Valid: `kapu`, `seni`, `ralo`
- Invalid: `kazk`, `zzop`, `xoae`

---

## 3. Roots
If we had no limitations, we could create 19*7 = 133 consonant-vowel roots. This section will probably change a lot.

### 3.1 Nouns
| **Root** | **Meaning**       |
|----------|-------------------|
| `ra`     | thing/object      |
| `ni`     | place/location    |
| `to`     | person/agent      |
| `se`     | time/moment       |
| `na`     | none/nothing      |
| `fu`     | function/purpose  |
| `lo`     | logic/truth       |

### 3.2 Verbs
| **Root** | **Meaning**       |
|----------|-------------------|
| `ko`     | move/motion       |
| `vi`     | see/visualize     |
| `po`     | create/make       |
| `za`     | exist/be          |
| `ba`     | start/begin       |
| `di`     | finish/end        |
| `mo`     | modify/change     |
| `su`     | supply/give       |
| `ta`     | take/receive      |

### 3.3 Modifiers
| **Root** | **Meaning**       |
|----------|-------------------|
| `un`     | negate/not        |
| `tri`    | three/third       |
| `sub`    | fraction/part     |
| `wa`     | wide/expand       |
| `li`     | limit/restrict    |
| `re`     | repeat/do again   |
| `ke`     | question          |

### 3.4 Logical and Probabilistic Operators
| **Root** | **Meaning**       |
|----------|-------------------|
| `an`     | and               |
| `or`     | or                |
| `if`     | conditional       |
| `prob`   | probably          |
| `lik`    | likely            |
| `unlik`  | unlikely          |
| `noc`    | not necessarily   |
| `xor`    | exclusive or      |
| `all`    | all (universal)   |
| `exi`    | exists            |

### 3.5 Directions
| **Root** | **Meaning**       |
|----------|-------------------|
| `x`      | forward           |
| `y`      | left              |
| `z`      | upward            |
| `neg`    | backward/down     |

### 3.6 States and Affirmations
| **Root** | **Meaning**       |
|----------|-------------------|
| `ye`     | yes               |
| `no`     | no                |
| `me`     | maybe             |
| `ok`     | acceptable/agree  |
| `koe`    | disagree          |


### 3.7 Reserved Roots
| **Reserved Roots** |
|---------------------|
| `be`, `ti`, `ka`, `so`, `nu`, `le`, `pa`, `ku`, `ri`, `da`, `vo`, `ma`, `bo`, `ze` |

### 3.8 Remaining Roots
Below is the list of unused Consonant-Vowel (CV) combinations, available for future use:

`pa`, `pe`, `pi`, `po`, `pu`, `pæ`, `pɒ`,  
`ta`, `te`, `ti`, `to`, `tu`, `tæ`, `tɒ`,  
`ka`, `ke`, `ki`, `ko`, `ku`, `kæ`, `kɒ`,  
`ba`, `be`, `bi`, `bo`, `bu`, `bæ`, `bɒ`,  
`da`, `de`, `di`, `do`, `du`, `dæ`, `dɒ`,  
`ga`, `ge`, `gi`, `go`, `gu`, `gæ`, `gɒ`,  
`fa`, `fe`, `fi`, `fo`, `fu`, `fæ`, `fɒ`,  
`sa`, `se`, `si`, `so`, `su`, `sæ`, `sɒ`,  
`va`, `ve`, `vi`, `vo`, `vu`, `væ`, `vɒ`,  
`la`, `le`, `li`, `lo`, `lu`, `læ`, `lɒ`,  
`ha`, `he`, `hi`, `ho`, `hu`, `hæ`, `hɒ`,  
`ma`, `me`, `mi`, `mo`, `mu`, `mæ`, `mɒ`,  
`na`, `ne`, `ni`, `no`, `nu`, `næ`, `nɒ`,  
`ra`, `re`, `ri`, `ro`, `ru`, `ræ`, `rɒ`,  
`za`, `ze`, `zi`, `zo`, `zu`, `zæ`, `zɒ`,  
`xa`, `xe`, `xi`, `xo`, `xu`, `xæ`, `xɒ`.

## 4. Conjugation, Pluralization, and Tenses

### 4.1 Verb Conjugation
To express tenses, reserved roots are appended to verbs. This ensures clarity and consistency. The tense markers are as follows:

| **Tense**     | **Root** | **Example**           | **Meaning**             |
|---------------|----------|-----------------------|-------------------------|
| Present       | `-na`    | `run-na`             | "runs"                 |
| Past          | `-ta`    | `run-ta`             | "ran"                  |
| Future        | `-sa`    | `run-sa`             | "will run"             |
| Continuous    | `-ka`    | `run-ka`             | "is running"           |
| Perfect       | `-da`    | `run-da`             | "has run"              |
| Conditional   | `-mo`    | `run-mo`             | "might run"            |
| Imperative    | `-lo`    | `run-lo`             | "run!"                 |

#### Notes:
- **Negation**: Use a prefix (e.g., `un-`) for negation.
  - Example: `un-run-na` → "does not run."

### 4.2 Noun Pluralization
Nouns are singular by default. To indicate plural forms, a specific suffix is appended:

| **Form**   | **Root** | **Example**          | **Meaning**           |
|------------|----------|----------------------|-----------------------|
| Singular   | -        | `child`             | "child"              |
| Plural     | `-li`    | `child-li`          | "children"           |

#### Optional: Count Prefixes
Use reserved prefixes for specific numbers if needed:
- `two-child` → "two children."
- `many-child` → "a lot of children."

### 4.3 Reserved Roots for Conjugation and Pluralization
| **Reserved Roots** | **Usage**       |
|---------------------|----------------|
| `-na`, `-ta`, `-sa`, `-ka`, `-da`, `-mo`, `-lo` | Verb tenses    |
| `-li`              | Noun pluralization |

### 4.4 