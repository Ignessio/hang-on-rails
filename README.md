# README

# Game scheme

# model Game belons_to :word

            games
------------------------------
id       |  guesses  |  word_id
------------------------------
bigint   |  array    |  bigint
------------------------------
1        |  [К, Ш]   |  1

# model Word has_many :games

            words
---------------------
id       |  text
---------------------
bigint   |  string
---------------------
1        |  РУБИ
