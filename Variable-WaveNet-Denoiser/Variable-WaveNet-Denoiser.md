# Variable WaveNet Denoiser (WIP)
Reseacher: Deep_Black_Sky (dive.into.the.black.sky.deeper@gmail.com)

## Abstruct

## Introduction
　人は雑音下においても、特定の人物から発せられる発話を聞き取ることができるとされている。
これは「カクテルパーティー効果」と呼ばれる。
しかし、（私のような）注意選択機能の乏しい人はその効果の恩恵を得ることができないようだ。

　これを補助する目的とする先行研究は存在する[1]。
WaveNetを用いて、雑音下の音声のみを抽出する試みである。
しかし、著者が述べてるように特定の人物の音声しか抽出できないことが欠点である。

　そこで、VAEにより発話者の音声特徴量を潜在変数上にマッピング、多数の発話者の特徴をモーフ化し、それを考慮した雑音除去のネットワークを提案する。

## Related work
### VAE

### WaveNet

## Variable WaveNet Denoiser (VWND)
　Variable WaveNet DenoiserはVAEにより音声を潜在特徴量に変換するEncoderと、音声から雑音を除去するDenoiserより構成される。

### Encoder

### Denoiser

## Experiments

## Conclusion

## References
[1] 深層学習を用いて特定の人物の声“だけ”抽出する、音声分離技術のしくみ, https://logmi.jp/tech/articles/301306/
