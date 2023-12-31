# SPC: Synthetic-Persona-Chat Dataset
We introduce the Synthetic-Persona-Chat dataset, a persona-based conversational dataset, consisting of two parts. The first part, consisting of 4,723 personas and 10,906 conversations, is an extension to Persona-Chat, which has the same user profile pairs as Persona-Chat but new synthetic conversations, with the same train/validation/test split as Persona-Chat. The second part consists of 5,648 new, synthetic personas, and 11,001 conversations between them. Synthetic-Persona-Chat is created using the Generator-Critic framework introduced in [Faithful Persona-based Conversational Dataset Generation with Large Language Models](https://arxiv.org/abs/2312.10007).

Each conversation in the dataset has the following format:

```
{
  "User 1 Personas":[],
  "User 2 Personas":[],
  "Conversation":[]
}
```

## Citation
If you found SPC useful, please use the following citation.
```
@misc{jandaghi2023faithful,
      title={Faithful Persona-based Conversational Dataset Generation with Large Language Models}, 
      author={Pegah Jandaghi and XiangHai Sheng and Xinyi Bai and Jay Pujara and Hakim Sidahmed},
      year={2023},
      eprint={2312.10007},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## License
[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Contact
* Pegah Jandaghi (jandaghi@usc.edu)
* Xianghai Sheng (xhs@google.com)
* Xinyi Bai (shinii@google.com)
* Jay Pujara (jpujara@isi.edu)
* Hakim Sidahmed (hsidahmed@google.com)
