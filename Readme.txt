WARNING: I AM NOT RESPONSIBLE FOR YOUR LOST DATA, OR MISUSE OF AI. KEEP BACKUPS OF ANY FILES YOU USE THIS 'PRE-COMPRESSION' ON. THIS IS INCOMPLETE PROGRAM AND ANY DATA YOU CODE THIS WAY IS VERY LIKELY TO BE CORRUPTED AND LOST FOREVER, OPTIMIZATIONS HAVE NOT BEEN MADE, AND IT DOES NOT YET HAVE A FINE-TUNED DECODING LLM. YOU WOULD HAVE TO USE AN UNTUNED LLM. YOU HAVE BEEN WARNED.  

Ambiguous-AI-Assisted-Text-Codec
(Precompression algorithm that makes your compression more compressive)

It's all in the title. Actually, the code is only the pre-compression part, which for us is simpler than the post-decompression part. The code was written using GPT 3.5, and what it does is generate a modified document before compression is used. The code removes the least commonly occurring symbol, which has the longest code, and assigns to its positions instead the most commonly occurring symbol, which has the shortest code. This is repeated for the second least common and second most common symbol, and so on.

You can also run the program on your text twice, which demonstrates the working principle quite well. However, I haven't gotten an AI to decode that yet. 

How to: Simply run the encoder on your text document. Next, use the compression of your choice. To decode, unzip the file then feed the document to an LLM. With one layer of pre-compression LLMs will usually give you back something correct or very close to the original text. 
