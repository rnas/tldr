# say

<<<<<<< HEAD
> Uses text to speech to speak through the default sound device

- Speak a phrase aloud

`say "I like to ride my bike.`

- Speak a file aloud

`say -f {{filename}}`

- Create an AAC compressed audio file with the spoken text

`say -o {{filename.m4a}} "Everyone loves iTunes"`
=======
> Converts text to speech.

- Say a phrase aloud:

`say {{"I like to ride my bike."}}`

- Read a file aloud:

`say -f {{filename.txt}}`

- Say a phrase with a custom voice and speech rate:

`say -v {{voice}} -r {{words_per_minute}} {{"I'm sorry Dave, I can't let you do that."}}`

- List the available voices:

`say -v ?`

- Create an audio file of the spoken text:

`say -o {{filename.aiff}} {{"Here's to the Crazy Ones."}}`
>>>>>>> upstream/master
