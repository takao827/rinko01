<<<<<<< HEAD
# 演習問題
## 演習の前準備
1. git hubのアカウントを作成  
2. ローカルの作業用PCにgit hubアカウントを登録  
   ```git config --global user.name "アカウント名"```  
   ```git config --global user.email "メールアドレス"```  
3. git hubにリモートリポジトリを作成  
4. ローカルに作業用リポジトリを作成 (作業用ディレクトリを作成し、そこに移動して```git init```)  
5. リモートリポジトリの登録  
   ```git remote add origin <リモートリポジトリのリンク>```  
6. ローカルリポジトリで何かしらのファイルを作成し、リモートリポジトリに反映  
   (例)  
   ```touch test.txt``` (何かしらのファイル作成)  
   ```git add .```   
   ```git commit -m "initial commit"```  
   ```git push origin master```  

### 以降は各班、各自取り組んでください！

## __初級問題__
### マスターブランチでコンフリクト祭り！！
班員に配られた別々の編集内容を各々がローカルのマスターブランチで編集を行い、編集できたらpushせよ  
コンフリクトを解消しつつ、班員全ての編集内容を反映させたファイルを完成させよ  


## __発展問題__
### いろんなgitコマンドを覚えよう！！
問0：masterブランチからchallengeブランチへ移動しなさい  
challengeブランチはすでに生成されているため、ブランチを新しく生成する必要はありません  
（以下の問題もchallengeブランチで行う）  
challengeブランチではusers.csvファイルに様々な編集を加えたコミットを積み重ねている  
それらのコミットログを用いて以下の演習を行う  
ヒント：今までのコミットログを見るには ```git log --graph``` を使うと便利です！！

問1：最新のコミットからコミットメッセージが「佐藤さんの要望」のコミットまでの変更内容を取り消しなさい（「佐藤さんの要望」のコミット自体は残す）

問2：やはり、コミットメッセージが「森さんの要望」までを取り消す方がよかったため、そこまで戻しなさい（「森さんの要望」のコミット自体は残す）

問3：「森さんの要望」というコミットメッセージを「林さんの要望」に直しなさい

問4：コミットメッセージが「吉田さんの要望」というコミットのみを取り消しなさい  
ただし、コミットを取り消したというログは残しておくこと

問5：コミットメッセージが「加藤さんの要望」のコミットのみをmasterブランチに反映させなさい  
コンフリクトが起きた場合はchallengeブランチ側の編集内容を優先すること

問6：コミットメッセージが「木村さんの要望」となっているコミットを全て1まとめにし、コミットメッセージを「木村さんの全要望」としなさい  
また、まとめたコミットの位置は一番最後の「木村さんの要望」の所にまとめておくこと（佐藤さんの要望の1つ前に位置する）

問7：問6でまとめたコミットの内容を以下のように編集しなさい  
編集内容：「木村 翼」さんの数値に100加算する

問8：challengeブランチでのコミット履歴を残したまま、masterへmergeせよ

### お疲れ様！これで君もGitマスターだ！！
=======
# rinko01
>>>>>>> 5968b7dc0b0518a7e00b643efe1a3cb86e64a944
