# Aclarar Videos IA 🌙

App web que aclara automáticamente videos oscuros o grabados de noche y mejora su calidad con IA. Todo se procesa en tu dispositivo; nada se sube a internet.

**Abrir:** https://cheto321.github.io/aclarar-videos/

## Créditos y licencias
- **Zero-DCE++** (Li, Guo, Loy) – aclarado de poca luz. [Li-Chongyi/Zero-DCE_extension](https://github.com/Li-Chongyi/Zero-DCE_extension). Licencia **CC BY-NC 4.0** (solo uso no comercial / investigación).
- **Real-ESRGAN realesr-general-x4v3** (Xintao Wang et al.) – súper resolución. [xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN). Licencia BSD-3-Clause.
- **realesr-general-wdn-x4v3** (variante de reducción de ruido, mismo repositorio, BSD-3) – mezclada con la anterior según el control "Reducción de ruido IA".
- **onnxruntime-web 1.31.1** (Microsoft) – MIT.
- **mp4-muxer** (Vanilagy) – MIT.
- **coi-serviceworker** (gzuidhof) – MIT.

Los modelos fueron convertidos a ONNX sin modificar sus pesos. Por la licencia de Zero-DCE++, este proyecto es de uso personal y no comercial.
