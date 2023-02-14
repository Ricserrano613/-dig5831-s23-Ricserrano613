# -dig5831-s23-Ricserrano613
Creative Project 1: Text Generation
Performed on 2/10/23

This is a custom story generated entirely through ChatGPT, then re-modeled and edited, then placed into GPT-2 for further text generation. The results from this experiment were surprising as I had not anticipated GPT-2's unique capabilities. 

I wanted to create a fictional story of an athlete starting from their days as a youth to eventually becomming one of the greatest basketball players of all time. This would recquire much time and thought processing so I instructed ChatGPT saying: "Can you write me a fictional story about a young basketball prospect who eventually makes his way to becoming one of the greatest NBA players of all time?". 

The result was a text generated story about a fictional player named Kyle Johnson who eventually made his way into becomming one of the greatest NBA players of all time, just as I had envisioned. 

To further explore this text generation, I had taken the modified story and plugged it into GPT-2 with these parameters before running: 
sess = gpt2.start_tf_sess()

gpt2.finetune(sess,
              dataset=file_name,
              model_name='124M',
              steps=50,
              restore_from='fresh',
              run_name='run1',
              print_every=10,
              sample_every=10,
              save_every=500
              )

The result was astounding, GPT-2 had created an anthology of stories off of what ChatGPT had generated for me. Instead of 1 character (Kyle), there was now 2 added characters (Dennison and Ryan), each with their own unique backstory. 

Although it was not complete, the story was missing logical elements such as a full name and the fact multiple words and phrases were repeated. I had simply decided to go back to ChatGPT and prompt it to give me a brief backstory on both characters and add last names for both. The results were unique generated stories for Ryan Williams and Dennison Smith. So I combined all three stories, took it back into Microsoft word to re-edit the stories and kept them at 3 different stories in 1 anthology. 
