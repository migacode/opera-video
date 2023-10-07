# opera-video
Opera Video Repair Tool (für Ubuntu/Debian)

Nach der Installation von Opera per Download von den Original-Seiten (nicht als Snap-App) bzw. nach Updates des Original-Opera kann es passieren, dass Videos nicht mehr abgespielt werden, da Opera einen ungeeigneten FFMPEG-Decoder verwendet. Daher muss dieser durch einen anderen Decoder ersetzt werden. Dieses Tool sucht eine passende libbffmpeg-Bibliothek und bindet diese in Opera ein. Selbstverständlich wird die entsprechende Original-Datei vorher gesichert. Hinweis: Es muss eine geeignete libbffmpeg.so auf dem System installiert sein, wie sie bspw. in Chromium enthalten ist.
