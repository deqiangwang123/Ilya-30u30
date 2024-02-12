# Ilya-30u30
- [Ilya 30u30 arc.net folder](https://arc.net/folder/D0472A20-9C20-4D3F-B145-D2865C0A9FEE)
- [Ilya 30u30 folder - archive.today](https://archive.is/aciJR)

<div style="width: 300px; margin: 0 auto;">
    <img src="./imgs/GAoQQgMaQAAc96H.jpg" style="width: 100%; display: block; margin: auto;">
</div>

## useful commands
very cool tool: [arxiv-downloader — Github repo](https://github.com/braun-steven/arxiv-downloader)

```powershell
pipx install arxiv-downloader
```

use an array to loop all arxiv listed URLs with `pwsh`
```powershell

$urls = @(
    "https://arxiv.org/pdf/1511.07122.pdf",
    "https://arxiv.org/pdf/1511.07122.pdf",
    "https://arxiv.org/pdf/1704.01212.pdf",
    "https://arxiv.org/pdf/1706.03762.pdf",
    "https://arxiv.org/pdf/1409.0473.pdf",
    "https://arxiv.org/pdf/1603.05027.pdf",
    "https://arxiv.org/pdf/1706.01427.pdf",
    "https://arxiv.org/pdf/1611.02731.pdf",
    "https://arxiv.org/pdf/1806.01822.pdf",
    "https://arxiv.org/pdf/1405.6903.pdf",
    "https://arxiv.org/pdf/1410.5401.pdf",
    "https://arxiv.org/pdf/1512.02595.pdf",
    "https://arxiv.org/pdf/2001.08361.pdf",
# this one won't work because of /math, so: > curl -LJO "https://arxiv.org/pdf/math/0406077.pdf"
)

foreach ($url in $urls) {
    arxiv-downloader --url $url
}
```
use `curl` for non-arxiv papers:
```powershell
$curlUrls = @(
"https://www.cs.toronto.edu/~hinton/absps/colt93.pdf",
"https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf"
)
foreach ($curlUrl in $curlUrls){
  curl -LJO $curlUrl
}
```
`curl` for books:
```powershell
$curlBooks = @(
  "https://www.vetta.org/documents/Machine_Super_Intelligence.pdf"
  "https://www.lirmm.fr/~ashen/kolmbook-eng-scan.pdf"
)
foreach ($curlBook in $curlBooks) {
  curl -LJO $curlBook
}
```

## lists
- - [ ] [The Annotated Transformer — blog](https://nlp.seas.harvard.edu/annotated-transformer/)
- - [ ] [The First Law of Complexodynamics — blog](https://scottaaronson.blog/?p=762)
- - [ ] [The Unreasonable Effectiveness of Recurrent Neural Networks — (Andrej Karpathy blog)](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- - [ ] [Understanding LSTM Networks – colah’s blog — blog](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- - [ ] [Recurrent Neural Network Regularization — arxiv.org](https://arxiv.org/pdf/1409.2329.pdf)
- - [ ] [Keeping NN Simple by Minimizing the Description Legnth of the Weights — PDF](https://www.cs.toronto.edu/~hinton/absps/colt93.pdf)
- - [ ] [Pointer Networks — arxiv.org](https://arxiv.org/pdf/1506.03134.pdf)
- - [ ] [ImageNet Classification with Deep Convolutional Neural Networks — PDF](https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
- - [ ] [Order Matters: Sequence to sequence for sets — arxiv.org](https://arxiv.org/pdf/1511.06391.pdf)
- - [ ] [GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism — arxiv.org](https://arxiv.org/pdf/1811.06965.pdf)
- - [ ] [Deep Residual Learning for Image Recognition — arxiv.org](https://arxiv.org/pdf/1512.03385.pdf)
- - [ ] [Multi-Scale Context Aggregation by Dilated Convolutions — arxiv.org](https://arxiv.org/pdf/1511.07122.pdf)
- - [ ] [Neural Message Passing for Quantum Chemistry — arxiv.org](https://arxiv.org/pdf/1704.01212.pdf)
- - [ ] [Attention Is All You Need — arxiv.org](https://arxiv.org/pdf/1706.03762.pdf)
- - [ ] [Neural Machine Translation by Jointly Learning to Align and Translate — arxiv.org](https://arxiv.org/pdf/1409.0473.pdf)
- - [ ] [Identity Mappings in Deep Residual Networks — arxiv.org](https://arxiv.org/pdf/1603.05027.pdf)
- - [ ] [A simple neural network module for relational reasoning — arxiv.org](https://arxiv.org/pdf/1706.01427.pdf)
- - [ ] [Variational Lossy Autoencoder — arxiv.org](https://arxiv.org/pdf/1611.02731.pdf)
- - [ ] [Relational recurrent neural networks — arxiv.org](https://arxiv.org/pdf/1806.01822.pdf)
- - [ ] [Quantifying the Rise and Fall of Complexity in Closed Systems: The Coffee Automaton — arxiv.org](https://arxiv.org/pdf/1405.6903.pdf)
- - [ ] [Neural Turing Machines — arxiv.org](https://arxiv.org/pdf/1410.5401.pdf)
- - [ ] [Deep Speech 2: End-to-End Speech Recognition in English and Mandarin — arxiv.org](https://arxiv.org/pdf/1512.02595.pdf)
- - [ ] [Scaling Laws for Neural Language Models — arxiv.org](https://arxiv.org/pdf/2001.08361.pdf)
- - [ ] [A tutorial introduction to the minimum description length principle — arxiv.org](https://arxiv.org/pdf/math/0406077.pdf)
- - [ ] [Machine Super Intelligence by Shane Legg | BookVersion.dvi — book](https://www.vetta.org/documents/Machine_Super_Intelligence.pdf)
- - [ ] [Kolmogorov Complexity and Algorithmic Randomness | lirmm.fr — book](https://www.lirmm.fr/~ashen/kolmbook-eng-scan.pdf)
- - [ ] [CS231n Convolutional Neural Networks for Visual Recognition — course](https://cs231n.github.io/)

