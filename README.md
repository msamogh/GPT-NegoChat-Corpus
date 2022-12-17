# GPT-Negochat: A *more realistic* corpus of negotiation dialogues

The **GPT-Negochat** corpus is a modified version of the original Negochat corpus, which contains negotiation dialogues between an Employer and a Candidate. The "Candidate" utterances in the original corpus were generated using a template-based NLG module and therefore, sound robotic and in general, do not sound convincingly real.

GPT-Negochat is the result of using GPT-3 to modify this original corpus to make the dialogues resemble actual job-negotiation dialogues more closely while still retaining the original meaning of the utterances.

In addition to rephrasing the utterances, a small set of highly unrealistic dialogue segments have been removed in GPT-Negochat without affecting the coherence of the surrounding dialogue.

<img width="1151" alt="image" src="https://user-images.githubusercontent.com/1230386/208210534-4c177690-b393-41a4-9d17-c1b170f2d0d6.png">


## Reference(s)
If you're using this dataset, please cite this repository and its owner, Amogh Mannekote.

Also cite the following original work:
```latex
@inproceedings{konovalov2016negochat,
  title={The Negochat Corpus of Human-agent Negotiation Dialogues},
  author={Konovalov, Vasily and Artstein, Ron and Melamud, Oren and Dagan, Ido},
  booktitle={Proceedings of the 10th International Conference on Language Resources and Evaluation, LREC 2016},
  year={2016},
  pages={3141-3145},
  url={www.lrec-conf.org/proceedings/lrec2016/pdf/240_Paper.pdf}
}
```

