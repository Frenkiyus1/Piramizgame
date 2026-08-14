[ OVERVIEW ]
Piramizgame la du an thu nghiem phat trien/clone lai mot tua game 
nham muc dich hoc tap, nghiên cuu co che gameplay (game mechanics), 
xu ly va cham va toi uu hoa hieu nang.

------------------------------------------------------------------------
[ TECH STACK ]
- Engine / Framework: Unity / Godot / Pygame / Raylib / HTML5 Canvas
- Ngon ngu lap trinh: C# / C++ / Python / JavaScript / TypeScript
- Do hoa & Asset   : Pixel Art / Sprite Sheet / 3D Models
- Am thanh         : WAV / MP3 (BGM & SFX)

------------------------------------------------------------------------
[ KEY FEATURES ]
[x] Gameplay co ban: Di chuyen, tan cong / nhay / tuong tac theo game goc.
[x] He thong diem so & Cap do: Luu ky luc diem (High Score) va tang do kho.
[x] Giao dien nguoi dung (UI): Man hinh bat dau, bang dieu khien, Game Over.
[x] Hieu ung am thanh & Hinh anh: Am thanh nen, hieu ung va cham/chien thang.
[ ] (Sap co) Che do choi nhieu nguoi (Multiplayer) / Them man choi moi.

------------------------------------------------------------------------
[ CONTROLS ]
- Di chuyen            : W, A, S, D hoac cac phim Mui ten
- Hanh dong / Tan cong : Space / J / Chuot trai
- Tam dung (Pause)     : Esc / P
- Choi lai (Restart)   : R

------------------------------------------------------------------------
[ GETTING STARTED ]

1. Clone repository:
   git clone https://github.com/Frenkiyus1/Testclonegame.git
   cd Testclonegame

2. Cai dat thu vien phu thuoc (neu co):
   # Neu la Web Game:
   npm install

   # Neu la Python/Pygame:
   pip install -r requirements.txt

3. Chay du an:
   python main.py  (Hoac mo du an bang Unity / Godot Editor)

------------------------------------------------------------------------
[ PROJECT STRUCTURE ]
Piramizgame/
├── assets/          # Chai tai nguyen (Hinh anh, Am thanh, Font)
│   ├── images/
│   └── audio/
├── src/             # Ma nguon chinh cua Game
│   ├── components/  # Co che doi tuong (Player, Enemy, Map,...)
│   └── utils/       # Cac ham ho tro
├── README.txt       # Tai lieu huong dan
└── main.ext         # File khoi chay chinh

------------------------------------------------------------------------
[ DONG GOP & GIAY PHEN / CONTRIBUTING & LICENSE ]
- Moi dong gop deu duoc hoan nghenh qua Pull Request tren GitHub.
- Giay phep: MIT License.
========================================================================
