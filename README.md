# Potholes Peru 2026 — grouped test and night extra

Hold-out used in:

**Detección y segmentación de baches en vista de parabrisas: hold-out agrupado y despliegue en smartphone**  
Yzquierdo Sanchez, B., & Chambi Aguilar, J. D. (2026). Universidad Peruana Unión.

## Cite

Yzquierdo Sanchez, B. (2026). *potholes país de Perú 2026 - test* (Version V1-test) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23018021

Also: https://github.com/BenavidezYzquierdoSanchez/data_pothole

## What this repository is

| Folder | Role | Do not mix with |
|---|---|---|
| `potholes-2026-test/` | Official grouped hold-out | Training images |
| `data-noche-test/` | Extra night set (out of split) | The 0.775 mAP figure |

Official test: **828** images with object, **2 530** instances.  
Night extra: **120** frames, not in the 828.

## Headline numbers (do not average them)

| Set | Model | box mAP@0.5 | mask mAP@0.5 |
|---|---|---:|---:|
| Test 828 / 2 530 | YOLO26s-seg, 3 seeds | 0.775 ± 0.021 | 0.735 ± 0.029 |
| Same test | YOLO11s-seg, 1 seed | 0.777 | 0.733 |
| Night 120 | YOLO26s-seg, 3 seeds | 0.183 ± 0.013 | 0.170 ± 0.007 |

App: https://github.com/yzquierdo1802-cpu/pothole_android_yolo26n

## Licence

CC BY 4.0. Plates and faces blurred (Ley 29733).

benavidezy@upeu.edu.pe · jeson.chabi@upeu.edu.pe
