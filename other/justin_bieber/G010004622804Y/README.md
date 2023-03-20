# Encoder used

|<center>Codec</center>|<center>Encoder</center>|<center>Version</center>|
|:----|:------|:------|
|MPEG-1 Audio Layer III (MP3)|LAME|3.100|
|AAC-LC (Advanced Audio Codec)|qaac|2.76|
|HE-AAC v1 (Advanced Audio Codec)|qaac|2.76|
|HE-AAC v2 (Advanced Audio Codec)|fdkaac|1.0.5|
|Ogg Vorbis|oggenc|2.88 (libvorbis 1.3.7-aoTuV-b6.03 Lancer Mod)|
|Opus|opusenc|0.2-3-gf5f571b (libopus 1.3-26-ge85ed772)|
|FLAC (Free Lossless Audio Codec)|flac|1.4.2|

# Encoder Options

|<center>Codec</center>|<center>Sampling Rate</center>|
|:--|:--|
|AAC-LC|44100 Hz|
|HE-AAC|44100 Hz|
|Ogg Vorbis|44100 Hz|
|Opus|48000 Hz|

|<center>Folder Name</center>|<center>Codec</center>|<center>Rate Control Mode</center>|<center>Bitrate or quality</center>|<center>Encoder settings</center>|
|:--|:--|:--|:--|:--|
|mp3_vbr_q9|MP3|VBR|9|`-m j -q 0 -V 9 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q8|MP3|VBR|8|`-m j -q 0 -V 8 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q7|MP3|VBR|7|`-m j -q 0 -V 7 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q6|MP3|VBR|6|`-m j -q 0 -V 6 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q5|MP3|VBR|5|`-m j -q 0 -V 5 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q4|MP3|VBR|4|`-m j -q 0 -V 4 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q3|MP3|VBR|3|`-m j -q 0 -V 3 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q2|MP3|VBR|2|`-m j -q 0 -V 2 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q1|MP3|VBR|1|`-m j -q 0 -V 1 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_vbr_q0|MP3|VBR|0|`-m j -q 0 -V 0 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_32k|MP3|ABR|32|`-m j -q 0 --abr 32 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_40k|MP3|ABR|40|`-m j -q 0 --abr 40 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_48k|MP3|ABR|48|`-m j -q 0 --abr 48 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_56k|MP3|ABR|56|`-m j -q 0 --abr 56 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_64k|MP3|ABR|64|`-m j -q 0 --abr 64 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_80k|MP3|ABR|80|`-m j -q 0 --abr 80 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_96k|MP3|ABR|96|`-m j -q 0 --abr 96 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_112k|MP3|ABR|112|`-m j -q 0 --abr 112 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_128k|MP3|ABR|128|`-m j -q 0 --abr 128 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_160k|MP3|ABR|160|`-m j -q 0 --abr 160 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_192k|MP3|ABR|192|`-m j -q 0 --abr 192 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_224k|MP3|ABR|224|`-m j -q 0 --abr 224 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_256k|MP3|ABR|256|`-m j -q 0 --abr 256 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_abr_320k|MP3|ABR|320|`-m j -q 0 --abr 320 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_32k|MP3|CBR|32|`-m j -q 0 --cbr -b 32 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_40k|MP3|CBR|40|`-m j -q 0 --cbr -b 40 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_48k|MP3|CBR|48|`-m j -q 0 --cbr -b 48 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_56k|MP3|CBR|56|`-m j -q 0 --cbr -b 56 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_64k|MP3|CBR|64|`-m j -q 0 --cbr -b 64 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_80k|MP3|CBR|80|`-m j -q 0 --cbr -b 80 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_96k|MP3|CBR|96|`-m j -q 0 --cbr -b 96 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_112k|MP3|CBR|112|`-m j -q 0 --cbr -b 112 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_128k|MP3|CBR|128|`-m j -q 0 --cbr -b 128 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_160k|MP3|CBR|160|`-m j -q 0 --cbr -b 160 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_192k|MP3|CBR|192|`-m j -q 0 --cbr -b 192 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_224k|MP3|CBR|224|`-m j -q 0 --cbr -b 224 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_256k|MP3|CBR|256|`-m j -q 0 --cbr -b 256 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|mp3_cbr_320k|MP3|CBR|320|`-m j -q 0 --cbr -b 320 -p --lowpass 22 --lowpass-width 0.2 --resample 44.1`|
|aac_lc_tvbr_q0|AAC-LC|VBR|0|`-V 0 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q9|AAC-LC|VBR|9|`-V 9 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q18|AAC-LC|VBR|18|`-V 18 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q27|AAC-LC|VBR|27|`-V 27 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q36|AAC-LC|VBR|36|`-V 36 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q45|AAC-LC|VBR|45|`-V 45 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q54|AAC-LC|VBR|54|`-V 54 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q64|AAC-LC|VBR|64|`-V 64 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q73|AAC-LC|VBR|73|`-V 73 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q82|AAC-LC|VBR|82|`-V 82 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q91|AAC-LC|VBR|91|`-V 91 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q100|AAC-LC|VBR|100|`-V 100 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q109|AAC-LC|VBR|109|`-V 109 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q118|AAC-LC|VBR|118|`-V 118 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_tvbr_q127|AAC-LC|VBR|127|`-V 127 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_64k|AAC-LC|CVBR|64|`-v 64 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_72k|AAC-LC|CVBR|72|`-v 72 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_80k|AAC-LC|CVBR|80|`-v 80 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_96k|AAC-LC|CVBR|96|`-v 96 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_112k|AAC-LC|CVBR|112|`-v 112 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_128k|AAC-LC|CVBR|128|`-v 128 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_144k|AAC-LC|CVBR|144|`-v 144 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_160k|AAC-LC|CVBR|160|`-v 160 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_192k|AAC-LC|CVBR|192|`-v 192 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_224k|AAC-LC|CVBR|224|`-v 224 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_256k|AAC-LC|CVBR|256|`-v 256 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_288k|AAC-LC|CVBR|288|`-v 288 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cvbr_320k|AAC-LC|CVBR|320|`-v 320 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_64k|AAC-LC|ABR|64|`-a 64 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_72k|AAC-LC|ABR|72|`-a 72 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_80k|AAC-LC|ABR|80|`-a 80 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_96k|AAC-LC|ABR|96|`-a 96 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_112k|AAC-LC|ABR|112|`-a 112 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_128k|AAC-LC|ABR|128|`-a 128 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_144k|AAC-LC|ABR|144|`-a 144 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_160k|AAC-LC|ABR|160|`-a 160 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_192k|AAC-LC|ABR|192|`-a 192 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_224k|AAC-LC|ABR|224|`-a 224 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_256k|AAC-LC|ABR|256|`-a 256 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_288k|AAC-LC|ABR|288|`-a 288 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_abr_320k|AAC-LC|ABR|320|`-a 320 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_64k|AAC-LC|CBR|64|`-c 64 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_72k|AAC-LC|CBR|72|`-c 72 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_80k|AAC-LC|CBR|80|`-c 80 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_96k|AAC-LC|CBR|96|`-c 96 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_112k|AAC-LC|CBR|112|`-c 112 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_128k|AAC-LC|CBR|128|`-c 128 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_144k|AAC-LC|CBR|144|`-c 144 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_160k|AAC-LC|CBR|160|`-c 160 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_192k|AAC-LC|CBR|192|`-c 192 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_224k|AAC-LC|CBR|224|`-c 224 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_256k|AAC-LC|CBR|256|`-c 256 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_288k|AAC-LC|CBR|288|`-c 288 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_lc_cbr_320k|AAC-LC|CBR|320|`-c 320 -q 2 -r keep --no-delay --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_32k|HE-AAC v1|CVBR|32|`-v 32 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_40k|HE-AAC v1|CVBR|40|`-v 40 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_48k|HE-AAC v1|CVBR|48|`-v 48 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_56k|HE-AAC v1|CVBR|56|`-v 56 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_64k|HE-AAC v1|CVBR|64|`-v 64 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cvbr_80k|HE-AAC v1|CVBR|80|`-v 80 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_32k|HE-AAC v1|ABR|32|`-a 32 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_40k|HE-AAC v1|ABR|40|`-a 40 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_48k|HE-AAC v1|ABR|48|`-a 48 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_56k|HE-AAC v1|ABR|56|`-a 56 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_64k|HE-AAC v1|ABR|64|`-a 64 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_abr_80k|HE-AAC v1|ABR|80|`-a 80 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_32k|HE-AAC v1|CBR|32|`-c 32 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_40k|HE-AAC v1|CBR|40|`-c 40 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_48k|HE-AAC v1|CBR|48|`-c 48 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_56k|HE-AAC v1|CBR|56|`-c 56 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_64k|HE-AAC v1|CBR|64|`-c 64 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v1_cbr_80k|HE-AAC v1|CBR|80|`-c 80 -q 2 -r keep --lowpass 21498 --gapless-mode 0 --threading`|
|aac_he_v2_vbr_q1|HE-AAC v2|VBR|1|`-p 29 -m 1 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_vbr_q2|HE-AAC v2|VBR|2|`-p 29 -m 2 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_vbr_q3|HE-AAC v2|VBR|3|`-p 29 -m 3 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_vbr_q4|HE-AAC v2|VBR|4|`-p 29 -m 4 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_vbr_q5|HE-AAC v2|VBR|5|`-p 29 -m 5 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_8k|HE-AAC v2|CBR|8|`-p 29 -b 8 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_16k|HE-AAC v2|CBR|16|`-p 29 -b 16 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_24k|HE-AAC v2|CBR|24|`-p 29 -b 24 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_32k|HE-AAC v2|CBR|32|`-p 29 -b 32 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_40k|HE-AAC v2|CBR|40|`-p 29 -b 40 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_48k|HE-AAC v2|CBR|48|`-p 29 -b 48 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_56k|HE-AAC v2|CBR|56|`-p 29 -b 56 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_64k|HE-AAC v2|CBR|64|`-p 29 -b 64 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|aac_he_v2_cbr_80k|HE-AAC v2|CBR|80|`-p 29 -b 80 -m 0 -a 1 -s 2 -f 0 -G 0 --moov-before-mdat`|
|ogg_vbr_q-2|Ogg Vorbis|VBR|-2|`-q -2 --resample 44100 -S 0`|
|ogg_vbr_q-1|Ogg Vorbis|VBR|-1|`-q -1 --resample 44100 -S 0`|
|ogg_vbr_q0|Ogg Vorbis|VBR|0|`-q 0 --resample 44100 -S 0`|
|ogg_vbr_q1|Ogg Vorbis|VBR|1|`-q 1 --resample 44100 -S 0`|
|ogg_vbr_q2|Ogg Vorbis|VBR|2|`-q 2 --resample 44100 -S 0`|
|ogg_vbr_q3|Ogg Vorbis|VBR|3|`-q 3 --resample 44100 -S 0`|
|ogg_vbr_q4|Ogg Vorbis|VBR|4|`-q 4 --resample 44100 -S 0`|
|ogg_vbr_q5|Ogg Vorbis|VBR|5|`-q 5 --resample 44100 -S 0`|
|ogg_vbr_q6|Ogg Vorbis|VBR|6|`-q 6 --resample 44100 -S 0`|
|ogg_vbr_q7|Ogg Vorbis|VBR|7|`-q 7 --resample 44100 -S 0`|
|ogg_vbr_q8|Ogg Vorbis|VBR|8|`-q 8 --resample 44100 -S 0`|
|ogg_vbr_q9|Ogg Vorbis|VBR|9|`-q 9 --resample 44100 -S 0`|
|ogg_vbr_q10|Ogg Vorbis|VBR|10|`-q 10 --resample 44100 -S 0`|
|ogg_abr_32k|Ogg Vorbis|ABR|32|`-b 32 --resample 44100 -S 0`|
|ogg_abr_40k|Ogg Vorbis|ABR|40|`-b 40 --resample 44100 -S 0`|
|ogg_abr_48k|Ogg Vorbis|ABR|48|`-b 48 --resample 44100 -S 0`|
|ogg_abr_56k|Ogg Vorbis|ABR|56|`-b 56 --resample 44100 -S 0`|
|ogg_abr_64k|Ogg Vorbis|ABR|64|`-b 64 --resample 44100 -S 0`|
|ogg_abr_72k|Ogg Vorbis|ABR|72|`-b 72 --resample 44100 -S 0`|
|ogg_abr_80k|Ogg Vorbis|ABR|80|`-b 80 --resample 44100 -S 0`|
|ogg_abr_96k|Ogg Vorbis|ABR|96|`-b 96 --resample 44100 -S 0`|
|ogg_abr_112k|Ogg Vorbis|ABR|112|`-b 112 --resample 44100 -S 0`|
|ogg_abr_128k|Ogg Vorbis|ABR|128|`-b 128 --resample 44100 -S 0`|
|ogg_abr_144k|Ogg Vorbis|ABR|144|`-b 144 --resample 44100 -S 0`|
|ogg_abr_160k|Ogg Vorbis|ABR|160|`-b 160 --resample 44100 -S 0`|
|ogg_abr_192k|Ogg Vorbis|ABR|192|`-b 192 --resample 44100 -S 0`|
|ogg_abr_224k|Ogg Vorbis|ABR|224|`-b 224 --resample 44100 -S 0`|
|ogg_abr_256k|Ogg Vorbis|ABR|256|`-b 256 --resample 44100 -S 0`|
|ogg_abr_288k|Ogg Vorbis|ABR|288|`-b 288 --resample 44100 -S 0`|
|ogg_abr_320k|Ogg Vorbis|ABR|320|`-b 320 --resample 44100 -S 0`|
|ogg_cbr_32k|Ogg Vorbis|CBR|32|`-b 32 --managed -m 32 -M 32 --resample 44100 -S 0`|
|ogg_cbr_40k|Ogg Vorbis|CBR|40|`-b 40 --managed -m 40 -M 40 --resample 44100 -S 0`|
|ogg_cbr_48k|Ogg Vorbis|CBR|48|`-b 48 --managed -m 48 -M 48 --resample 44100 -S 0`|
|ogg_cbr_56k|Ogg Vorbis|CBR|56|`-b 56 --managed -m 56 -M 56 --resample 44100 -S 0`|
|ogg_cbr_64k|Ogg Vorbis|CBR|64|`-b 64 --managed -m 64 -M 64 --resample 44100 -S 0`|
|ogg_cbr_72k|Ogg Vorbis|CBR|72|`-b 72 --managed -m 72 -M 72 --resample 44100 -S 0`|
|ogg_cbr_80k|Ogg Vorbis|CBR|80|`-b 80 --managed -m 80 -M 80 --resample 44100 -S 0`|
|ogg_cbr_96k|Ogg Vorbis|CBR|96|`-b 96 --managed -m 96 -M 96 --resample 44100 -S 0`|
|ogg_cbr_112k|Ogg Vorbis|CBR|112|`-b 112 --managed -m 112 -M 112 --resample 44100 -S 0`|
|ogg_cbr_128k|Ogg Vorbis|CBR|128|`-b 128 --managed -m 128 -M 128 --resample 44100 -S 0`|
|ogg_cbr_144k|Ogg Vorbis|CBR|144|`-b 144 --managed -m 144 -M 144 --resample 44100 -S 0`|
|ogg_cbr_160k|Ogg Vorbis|CBR|160|`-b 160 --managed -m 160 -M 160 --resample 44100 -S 0`|
|ogg_cbr_192k|Ogg Vorbis|CBR|192|`-b 192 --managed -m 192 -M 192 --resample 44100 -S 0`|
|ogg_cbr_224k|Ogg Vorbis|CBR|224|`-b 224 --managed -m 224 -M 224 --resample 44100 -S 0`|
|ogg_cbr_256k|Ogg Vorbis|CBR|256|`-b 256 --managed -m 256 -M 256 --resample 44100 -S 0`|
|ogg_cbr_288k|Ogg Vorbis|CBR|288|`-b 288 --managed -m 288 -M 288 --resample 44100 -S 0`|
|ogg_cbr_320k|Ogg Vorbis|CBR|320|`-b 320 --managed -m 320 -M 320 --resample 44100 -S 0`|
|opus_vbr_8k|Opus|VBR|8|`--bitrate 8 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_16k|Opus|VBR|16|`--bitrate 16 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_24k|Opus|VBR|24|`--bitrate 24 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_32k|Opus|VBR|32|`--bitrate 32 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_40k|Opus|VBR|40|`--bitrate 40 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_48k|Opus|VBR|48|`--bitrate 48 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_56k|Opus|VBR|56|`--bitrate 56 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_64k|Opus|VBR|64|`--bitrate 64 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_72k|Opus|VBR|72|`--bitrate 72 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_80k|Opus|VBR|80|`--bitrate 80 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_96k|Opus|VBR|96|`--bitrate 96 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_112k|Opus|VBR|112|`--bitrate 112 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_128k|Opus|VBR|128|`--bitrate 128 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_144k|Opus|VBR|144|`--bitrate 144 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_160k|Opus|VBR|160|`--bitrate 160 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_192k|Opus|VBR|192|`--bitrate 192 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_224k|Opus|VBR|224|`--bitrate 224 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_256k|Opus|VBR|256|`--bitrate 256 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_288k|Opus|VBR|288|`--bitrate 288 --vbr --music --comp 10 --framesize 60`|
|opus_vbr_320k|Opus|VBR|320|`--bitrate 320 --vbr --music --comp 10 --framesize 60`|
|opus_cvbr_8k|Opus|CVBR|8|`--bitrate 8 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_16k|Opus|CVBR|16|`--bitrate 16 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_24k|Opus|CVBR|24|`--bitrate 24 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_32k|Opus|CVBR|32|`--bitrate 32 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_40k|Opus|CVBR|40|`--bitrate 40 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_48k|Opus|CVBR|48|`--bitrate 48 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_56k|Opus|CVBR|56|`--bitrate 56 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_64k|Opus|CVBR|64|`--bitrate 64 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_72k|Opus|CVBR|72|`--bitrate 72 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_80k|Opus|CVBR|80|`--bitrate 80 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_96k|Opus|CVBR|96|`--bitrate 96 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_112k|Opus|CVBR|112|`--bitrate 112 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_128k|Opus|CVBR|128|`--bitrate 128 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_144k|Opus|CVBR|144|`--bitrate 144 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_160k|Opus|CVBR|160|`--bitrate 160 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_192k|Opus|CVBR|192|`--bitrate 192 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_224k|Opus|CVBR|224|`--bitrate 224 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_256k|Opus|CVBR|256|`--bitrate 256 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_288k|Opus|CVBR|288|`--bitrate 288 --cvbr --music --comp 10 --framesize 60`|
|opus_cvbr_320k|Opus|CVBR|320|`--bitrate 320 --cvbr --music --comp 10 --framesize 60`|
|opus_cbr_8k|Opus|CBR|8|`--bitrate 8 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_16k|Opus|CBR|16|`--bitrate 16 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_24k|Opus|CBR|24|`--bitrate 24 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_32k|Opus|CBR|32|`--bitrate 32 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_40k|Opus|CBR|40|`--bitrate 40 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_48k|Opus|CBR|48|`--bitrate 48 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_56k|Opus|CBR|56|`--bitrate 56 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_64k|Opus|CBR|64|`--bitrate 64 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_72k|Opus|CBR|72|`--bitrate 72 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_80k|Opus|CBR|80|`--bitrate 80 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_96k|Opus|CBR|96|`--bitrate 96 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_112k|Opus|CBR|112|`--bitrate 112 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_128k|Opus|CBR|128|`--bitrate 128 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_144k|Opus|CBR|144|`--bitrate 144 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_160k|Opus|CBR|160|`--bitrate 160 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_192k|Opus|CBR|192|`--bitrate 192 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_224k|Opus|CBR|224|`--bitrate 224 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_256k|Opus|CBR|256|`--bitrate 256 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_288k|Opus|CBR|288|`--bitrate 288 --hard-cbr --music --comp 10 --framesize 60`|
|opus_cbr_320k|Opus|CBR|320|`--bitrate 320 --hard-cbr --music --comp 10 --framesize 60`|