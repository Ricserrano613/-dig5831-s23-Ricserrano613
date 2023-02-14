Instructions for creating/running NBA story. 

1. Go to openAI and open ChatGPT. 
2. Prompt ChatGPT to generate a fictional story about a young basketball prospect who eventually makes his way to becoming one of the greatest NBA players of all time
3. Insert results into microsoft word.
4. Edit/change text around to make more appealing/more logistical sense. 
5. Insert result into GPT-2. 
6. Run these parameters:
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
6. Insert results into new word document. 
7. Revisit ChatGPT and prompt to elaborate more on new characters created by GPT-2.
8. Input results into exisiting word document.
9. Edit/change text around to make more appealing/more logistical sense.
10. Save final results! 
