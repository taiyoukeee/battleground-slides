# battleground-slides

BattleGround（VRChat ワールド）のロードアウトスライドを、ワールド外から読み込むための配信用データです。

- `slides/<name>.y2k.bin` — 軽量版（Y2K "K" 形式、DXT1 比 約 60 % の VRAM）。専用シェーダーで表示します。
- `slides/<name>.q8.bin` — Quest/Android 用（ASTC 8×8、ASTC 6×6 比 56 %）。
- `slides/<name>.pc.bin` — PC 用 DXT1 そのまま版（ワールドに焼き込んだ画像と同一）。

VRChat の String Loading（`*.github.io` は許可ドメイン）で取得します。

## 収録

`slides/index.json` に一覧（ファイル名・サイズ・SHA-256）があります。

## 紹介動画

`video/intro_<名前>.mp4` — 1080p30 H.264、音声なし、faststart。VRChat の Unity 版ビデオプレイヤーで直接再生します（GitHub Pages は動画の許可リスト外のため Allow Untrusted URLs が必要）。
