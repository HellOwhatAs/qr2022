# qr2022
Generate QR code of the given string.
Supported characters:
```
['0', '1', '2', '3', '4', '5', '6', '7', '8', '9', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z', '$', '%', '*', '+', '-', '.', '/', ':', ' ']
```
## Install
```bat
pip install qr2022
```
## Usage
```python
from qr2022 import qrcode
import cv2
img=qrcode("HELLO WORLD")
cv2.imshow("qr",img)
cv2.waitKey(0)
```
