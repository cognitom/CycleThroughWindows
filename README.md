# Changing Window Command for Adobe Fireworks

Adobe Fireworks for Mac を使っていての不満点の一つとして、ウィンドウ切換えをキーボードから行えないというのがあります。それをスクリプトでなんとかしようプロジェクトです。

※注 : まだ、実用に堪えません (特にCS5環境だと)。改善案を教えて下さい ><

## Install

このリポジトリをMacにクローンしたら、Terminalから、

	ln -s "~/github/CycleThroughWindows/Cycle Through Windows.jsf" “/Applications/Adobe CS3/Adobe Fireworks CS3/Configuration/Commands/Cycle Through Windows.jsf”

などと実行して、シンボリックリンクをFireworksのCommandsフォルダに作成しておきましょう。拡張子をjsfにするのがポイントです。

## To Do

今の実装は非常に遅いので、もっとマシな方法を探す必要があります。

## License

と書くほどでもないですが、お好きに使ってください、というかフォークして改善してください。一応、MITライセンス。