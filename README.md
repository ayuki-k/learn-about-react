# learn-about-react
Learn about react, next

#開発環境を作成する上でのベース
- [node【公式】](https://hub.docker.com/_/node)
- [React開発を加速！ViteとDockerで作るシンプル開発環境入門](https://qiita.com/shoki-y/items/1be906c372c8a9a993a3)
- [***Docker ContainerでReact環境を作る](https://zenn.dev/teruroom/scraps/68e277624181fa)


#docker-fileを作る上での注意
- [nodeのDockerイメージのタグについているalpineとかslimが意味するもの](https://qiita.com/miriwo/items/52ea9ec1c2805137dd5a)
- [とりあえずでDockerイメージにAlpine Linuxを選択するのはやめましょうという話](https://engineering.nifty.co.jp/blog/26586)
- [Next.js開発環境構築にdocker composeを使い倒した話](https://zenn.dev/k_hojo/articles/318d18e0e5b9ac)
- [docker-compose の bind mount を1行で書くな](https://zenn.dev/sarisia/articles/0c1db052d09921#fn-bf4c-1)
- [DockerでReact環境構築【2023】](https://qiita.com/aka_ebi/items/79dd54982aeeb72aecf6)



```
docker-compose run --rm app sh -c 'npx create-react-app react-app --template typescript'
```

```
docker-compose run --rm app sh -c 'npm create vite@latest react-app -- --template react'
```