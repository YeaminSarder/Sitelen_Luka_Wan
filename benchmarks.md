# Definitions
- partition
  - the array eg. [['a', 't'], ['e', 'j', 'm'], ['i', 'p'], ['k', 'u', 'w'], ['l', 'o'], ['n', 's']]

- character group or group
  - groups of character. eg. ['a', 't']

- gchar of a character
  - index of the group that the character is in: eg gchar of 'j' is 1 in the above partition.

- TWL = tranformed word list
  - is the list you get after replacing each characters
  of a word with it's gchar

- character distribution:
  - frequency distribution of gchar in TWL

- first character distribution:
  - frequency distribution of gchar of the first character of a word among all words.

---

# calculations

- stdanderd deviation of character distribution of TWL:
  - may be useful if you are making a writting system
  - min: 7.503332592921628
    - [['a', 't'], ['e', 'j', 'm'], ['i', 'p'], ['k', 'u', 'w'], ['l', 'o'], ['n', 's']]
    - [105, 86, 94, 84, 91, 95]
  - max: 41.37511329289625
    - [['a', 'l'], ['e', 'k', 'w'], ['i', 'n', 't'], ['j', 'm', 'u'], ['o', 's'], ['p']]
    - [133, 103, 139, 67, 83, 30]
  - mean 92.5

- sd of first character distribution of TWL:
  - may be used to categorize words as uniform as possible
    - for example, I'm using this to build my toki pona keyboard layout
  - min: 0.983192080250175
    - [['a', 'p'], ['e', 's'], ['i', 'n', 't'], ['j', 'm', 'u'], ['k', 'w'], ['l', 'o']]
    - [23, 22, 22, 24, 24, 22]
  - max: 7.413950813612582
    - [['a', 'k', 'w'], ['e', 'l'], ['i', 'p'], ['j', 'm', 'o'], ['n', 's'], ['t', 'u']]
    - [33, 21, 18, 26, 27, 12]
  - mean 22.833333333333332

- based on word frequency:
  - *not computed*
- based on in group character similarity
  - on appearance of the characters:
    - *not computed*
  - on how the characters sound:
    - *not computed*
