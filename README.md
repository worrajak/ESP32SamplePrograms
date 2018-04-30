# ESP32 Arduino/Micropython サンプルプログラム

Interface誌2018年9月号に掲載したプログラムの全体です。

ESP32のArduinoとMicropythonでセンサデーターを読み、[IoTデーター可視化サービスAmbient](https://ambidata.io)に
送信し、可視化するプログラムです。

* Arduino/BME280_test: ArduinoでのBME280動作確認プログラム
* Arduino/Ambient_BME280: ArduinoでBME280のデーターをAmbientに送信するプログラム
* Arduino/Ambient_BME280_ds: ArduinoでBME280のデーターをAmbientに送信するプログラムで、送信と送信の間をDeepSleepするバージョン
* Micropython: MicropythonでBME280のデーターをAmbientに送信するプログラム