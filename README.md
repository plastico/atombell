# atombell

Making a bell system in home network betweenn M5AtomLite and M5AtomEcho.

Bell_Reciever:For a M5Atom Echo.
Play beep on get a signal to a network by espnow protocol.

Reference:
https://github.com/m5stack/M5Atom/tree/master/examples/ATOM_BASE/ATOM_SPK/PlayRawPCM

Bell_Sender:For a M5Atom Lite.
Send a signal to a network by espnow protocol.

please burn each ino files.

我が家の COVID19 対策用に宅内ベルシステムを作りました。
発信側に M5Atom Lite,受信側に M5Atom Echo を準備して ino ファイルを書き込んでください。

MAC アドレスは FFFFFF で発信、受信するので誤受信を避けるなら、特定の MAC に書き換えてください。

本当は Echo 二台でトランシーバーを作りたかったけど、リリース優先しました。
（どなたか拡張してくれるのを期待します。）
