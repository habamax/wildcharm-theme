# wildcharm-theme

Dark and light Emacs themes based on vim-wildcharm.

Should look mostly the same in GUI and TUI (terminal with 256 color support).

![image](https://github.com/habamax/wildcharm-theme/assets/234774/e47c5a49-c673-42d6-b466-a5a6ba36abbb)

![image](https://github.com/habamax/wildcharm-theme/assets/234774/3cee61e0-c416-4da5-b5ce-bc4ea747335d)


## Installation

Available on MELPA:

```
(add-to-list 'package-archives
             '("melpa" . "https://melpa.org/packages/") 'append)
```

- `M-x package-install RET wildcharm-theme RET` or
- `M-x package-install RET wildcharm-light-theme RET`


## Setup

No theme specific options are exposed, use regular Emacs elisp if needed, for example:

```emacs-lisp
(use-package wildcharm-theme
  :init
  (load-theme 'wildcharm t)
  :custom-face
  ;; org header sizes
  (org-level-1 ((t (:height 1.6))))
  (org-level-2 ((t (:height 1.4))))
  (org-level-3 ((t (:height 1.2))))
  ;; italic comments
  (font-lock-comment-face ((t (:slant italic)))))
```

or

```emacs-lisp
(use-package wildcharm-light-theme
  :init
  (load-theme 'wildcharm-light t)
  :custom-face
  ;; org header sizes
  (org-level-1 ((t (:height 1.6))))
  (org-level-2 ((t (:height 1.4))))
  (org-level-3 ((t (:height 1.2))))
  ;; italic comments
  (font-lock-comment-face ((t (:slant italic)))))
```

## Main colors

### Dark

| Color      | RGB       |                | Color          | RGB       |                |
|------------|-----------|----------------|----------------|-----------|----------------|
| Black      | `#000000` | ![#000000][0]  | Dark Grey      | `#808080` | ![#808080][8]  |
| Red        | `#D75F5F` | ![#D75F5F][1]  | Bright Red     | `#FF5F87` | ![#FF5F87][9]  |
| Green      | `#00AF5F` | ![#00AF5F][2]  | Bright Green   | `#00D75F` | ![#00D75F][10] |
| Yellow     | `#D78700` | ![#D78700][3]  | Bright Yellow  | `#FFAF00` | ![#FFAF00][11] |
| Blue       | `#0087D7` | ![#0087D7][4]  | Bright Blue    | `#00AFFF` | ![#00AFFF][12] |
| Magenta    | `#D787D7` | ![#D787D7][5]  | Bright Magenta | `#FF87FF` | ![#FF87FF][13] |
| Cyan       | `#00AFAF` | ![#00AFAF][6]  | Bright Cyan    | `#00D7D7` | ![#00D7D7][14] |
| Grey       | `#D0D0D0` | ![#D0D0D0][7]  | White          | `#FFFFFF` | ![#FFFFFF][15] |
| Purple     | `#875FFF` | ![#875FFF][28] | Comment        | `#87875F` | ![#87875F][27] |
| Foreground | `#D0D0D0` | ![#D0D0D0][7]  | Background     | `#121212` | ![#121212][16] |


### Light

| Color      | RGB       |                | Color          | RGB       |                |
|------------|-----------|----------------|----------------|-----------|----------------|
| Black      | `#000000` | ![#000000][0]  | Dark Grey      | `#808080` | ![#808080][8]  |
| Red        | `#AF0000` | ![#AF0000][17] | Bright Red     | `#D70000` | ![#D70000][23] |
| Green      | `#008700` | ![#008700][18] | Bright Green   | `#5FAF5F` | ![#5FAF5F][24] |
| Yellow     | `#AF5F00` | ![#AF5F00][19] | Bright Yellow  | `#D78700` | ![#D78700][3]  |
| Blue       | `#005FAF` | ![#005FAF][20] | Bright Blue    | `#0087D7` | ![#0087D7][4]  |
| Magenta    | `#870087` | ![#870087][21] | Bright Magenta | `#AF00AF` | ![#AF00AF][25] |
| Cyan       | `#005F5F` | ![#005F5F][22] | Bright Cyan    | `#008787` | ![#008787][26] |
| Grey       | `#D0D0D0` | ![#D0D0D0][7]  | White          | `#FFFFFF` | ![#FFFFFF][15] |
| Purple     | `#5F00D7` | ![#5F00D7][29] | Comment        | `#87875F` | ![#87875F][27] |
| Foreground | `#000000` | ![#000000][0]  | Background     | `#FFFFFF` | ![#FFFFFF][15] |


[0]: https://github.com/habamax/wildcharm-theme/assets/234774/1438b0cb-0dc7-483e-91ab-95be90b69bf1
[1]: https://github.com/habamax/wildcharm-theme/assets/234774/bf362c5e-99f1-4b07-a222-52efe382b3ab
[2]: https://github.com/habamax/wildcharm-theme/assets/234774/17a1d391-667c-4d79-b55d-627be6c67aa0
[3]: https://github.com/habamax/wildcharm-theme/assets/234774/22f46f5b-5b9c-4183-a9af-2591a2b5dab4
[4]: https://github.com/habamax/wildcharm-theme/assets/234774/ff5b881d-deb0-412e-a511-c22b79d6acc7
[5]: https://github.com/habamax/wildcharm-theme/assets/234774/9c8f8edc-aeb2-414a-ab5d-d54fabe471bb
[6]: https://github.com/habamax/wildcharm-theme/assets/234774/3d2e73a6-21f2-41fe-b7ae-710fc94ca734
[7]: https://github.com/habamax/wildcharm-theme/assets/234774/763bb4e1-e730-4637-80e8-d68bab7e52d7
[8]: https://github.com/habamax/wildcharm-theme/assets/234774/22eeff2d-1874-4c2f-b1a2-efe45e2fd322
[9]: https://github.com/habamax/wildcharm-theme/assets/234774/0f950b80-f096-4ff4-b5cf-465817bc9c44
[10]: https://github.com/habamax/wildcharm-theme/assets/234774/2e36f6e0-757c-4fb5-a34d-2658993a1103
[11]: https://github.com/habamax/wildcharm-theme/assets/234774/4c13093d-ba33-46d3-982d-458f3ad3c809
[12]: https://github.com/habamax/wildcharm-theme/assets/234774/b65473ab-0545-49f2-af43-8e06f20a9d6b
[13]: https://github.com/habamax/wildcharm-theme/assets/234774/07a25815-31a3-47c7-bf0c-7a24af50238c
[14]: https://github.com/habamax/wildcharm-theme/assets/234774/b01c7f57-1885-47d4-8eac-67e63fa5707c
[15]: https://github.com/habamax/wildcharm-theme/assets/234774/63a9613d-58de-4c80-9a3a-9c7211f3cd60
[16]: https://github.com/habamax/wildcharm-theme/assets/234774/b611a28a-d7bd-496a-bd8f-a7dc3655b2ba
[17]: https://github.com/habamax/wildcharm-theme/assets/234774/3a4da6b7-3771-44d9-b357-ae52616a385b
[18]: https://github.com/habamax/wildcharm-theme/assets/234774/00a11d33-fc0f-4f66-825f-f835928abcf8
[19]: https://github.com/habamax/wildcharm-theme/assets/234774/5467bc6d-f2aa-4a95-a3fe-041417560bba
[20]: https://github.com/habamax/wildcharm-theme/assets/234774/8afd7d26-ffe2-481e-b727-b50c73548cd4
[21]: https://github.com/habamax/wildcharm-theme/assets/234774/6b7fdebd-74fa-4925-89c1-4dc24247496d
[22]: https://github.com/habamax/wildcharm-theme/assets/234774/9a2a1628-d5ab-4099-8bcb-d3a8dd41d541
[23]: https://github.com/habamax/wildcharm-theme/assets/234774/40f67a14-c861-489e-8416-98ec0affbb95
[24]: https://github.com/habamax/wildcharm-theme/assets/234774/60d85b3c-3a8f-4f85-b8f0-54664077d53e
[25]: https://github.com/habamax/wildcharm-theme/assets/234774/161f6e9b-d2d4-44f8-bab5-3fe06da1c2bb
[26]: https://github.com/habamax/wildcharm-theme/assets/234774/3cfc3fe4-df7e-4f74-8fd8-6d9a50f7348d
[27]: https://github.com/habamax/wildcharm-theme/assets/234774/1c16de35-bba3-4685-ae98-3f362ee8ccdf
[28]: https://github.com/habamax/wildcharm-theme/assets/234774/03ee82dd-0904-4a18-8b6f-1c51b9a08786
[29]: https://github.com/habamax/wildcharm-theme/assets/234774/55e58edc-20e4-4ea5-9c40-a68e1132e3d8
