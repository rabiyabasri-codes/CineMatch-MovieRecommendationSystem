# 🎬 CineMatch - Local Poster Setup Guide

## Overview
The application is now set up to use **local poster images** instead of relying on the TMDB API. This means you have complete control over the movie posters and the application works **100% offline**.

## 📁 Folder Structure
```
MovieRecommendationSystem/
├── src/
│   ├── CineMatch.html          (Main application file)
│   ├── posters/                 (👈 Place poster images here)
│   ├── FileHandler.java
│   ├── Main.java
│   └── ... other files ...
├── POSTER_SETUP_GUIDE.md       (This file)
└── README.md
```

## 🖼️ How to Add Poster Images

### Step 1: Prepare Your Images
- **Size**: Recommended **342×513 pixels** (standard poster aspect ratio)
- **Format**: JPG, PNG, WebP
- **Quality**: Medium-high quality for best display
- **Filename**: Must match the filename mapping below

### Step 2: Image Naming Convention
All poster files use **numbered filenames** from `001.jpg` to `114.jpg`:

**Examples:**
- Movie 1 (The Dark Knight) → `001.jpg`
- Movie 2 (Inception) → `002.jpg`
- Movie 89 (3 Idiots - Bollywood) → `089.jpg`
- Movie 114 (Tumbbad - Bollywood) → `114.jpg`

### Step 3: Place Files in Poster Folder
1. Navigate to: `src/posters/`
2. Place all your poster images in this folder
3. Make sure filenames match exactly (001.jpg, 002.jpg, etc.)

### Step 4: Test the Application
- Open `CineMatch.html` in a web browser
- Navigate through different tabs (Trending, Bollywood, Top Rated, etc.)
- Posters should now display correctly
- If an image is missing, it shows a beautiful colored gradient placeholder (no broken images!)

## 📋 Complete Movie Poster Mapping

### Hollywood Action (001-020)
| ID | Filename | Movie Title |
|---|---|---|
| 001 | 001.jpg | The Dark Knight |
| 002 | 002.jpg | Inception |
| 003 | 003.jpg | Interstellar |
| 004 | 004.jpg | The Matrix |
| 005 | 005.jpg | Avengers: Endgame |
| 006 | 006.jpg | Mad Max: Fury Road |
| 007 | 007.jpg | John Wick |
| 008 | 008.jpg | Top Gun: Maverick |
| 009 | 009.jpg | Mission: Impossible – Fallout |
| 010 | 010.jpg | The Avengers |
| 011 | 011.jpg | Gladiator |
| 012 | 012.jpg | Batman Begins |
| 013 | 013.jpg | Spider-Man: No Way Home |
| 014 | 014.jpg | Black Panther |
| 015 | 015.jpg | 300 |
| 016 | 016.jpg | The Dark Knight Rises |
| 017 | 017.jpg | Iron Man |
| 018 | 018.jpg | Fast & Furious 7 |
| 019 | 019.jpg | Wonder Woman |
| 020 | 020.jpg | Captain America: Civil War |

### Crime / Thriller (021-036)
| ID | Filename | Movie Title |
|---|---|---|
| 021 | 021.jpg | The Godfather |
| 022 | 022.jpg | Pulp Fiction |
| 023 | 023.jpg | Fight Club |
| 024 | 024.jpg | Parasite |
| 025 | 025.jpg | Goodfellas |
| 026 | 026.jpg | The Silence of the Lambs |
| 027 | 027.jpg | The Wolf of Wall Street |
| 028 | 028.jpg | Se7en |
| 029 | 029.jpg | Joker |
| 030 | 030.jpg | Prisoners |
| 031 | 031.jpg | Knives Out |
| 032 | 032.jpg | Gone Girl |
| 033 | 033.jpg | No Country for Old Men |
| 034 | 034.jpg | Zodiac |
| 035 | 035.jpg | Heat |
| 036 | 036.jpg | Oldboy |

### Sci-Fi / Adventure (037-049)
| ID | Filename | Movie Title |
|---|---|---|
| 037 | 037.jpg | Dune |
| 038 | 038.jpg | Oppenheimer |
| 039 | 039.jpg | Avatar |
| 040 | 040.jpg | Blade Runner 2049 |
| 041 | 041.jpg | Arrival |
| 042 | 042.jpg | The Martian |
| 043 | 043.jpg | Gravity |
| 044 | 044.jpg | 2001: A Space Odyssey |
| 045 | 045.jpg | E.T. the Extra-Terrestrial |
| 046 | 046.jpg | Dune: Part Two |
| 047 | 047.jpg | Star Wars: A New Hope |
| 048 | 048.jpg | The Terminator |
| 049 | 049.jpg | Back to the Future |

### Drama (050-064)
| ID | Filename | Movie Title |
|---|---|---|
| 050 | 050.jpg | The Shawshank Redemption |
| 051 | 051.jpg | Forrest Gump |
| 052 | 052.jpg | Schindler's List |
| 053 | 053.jpg | Whiplash |
| 054 | 054.jpg | 12 Years a Slave |
| 055 | 055.jpg | The Pursuit of Happyness |
| 056 | 056.jpg | A Beautiful Mind |
| 057 | 057.jpg | American History X |
| 058 | 058.jpg | The Green Mile |
| 059 | 059.jpg | Good Will Hunting |
| 060 | 060.jpg | Titanic |
| 061 | 061.jpg | The Pianist |
| 062 | 062.jpg | Manchester by the Sea |
| 063 | 063.jpg | 1917 |
| 064 | 064.jpg | Parasite |

### Comedy (065-072)
| ID | Filename | Movie Title |
|---|---|---|
| 065 | 065.jpg | The Grand Budapest Hotel |
| 066 | 066.jpg | Superbad |
| 067 | 067.jpg | The Hangover |
| 068 | 068.jpg | Home Alone |
| 069 | 069.jpg | Game Night |
| 070 | 070.jpg | Bridesmaids |
| 071 | 071.jpg | Step Brothers |
| 072 | 072.jpg | Groundhog Day |

### Animation (073-081)
| ID | Filename | Movie Title |
|---|---|---|
| 073 | 073.jpg | Spider-Man: Into the Spider-Verse |
| 074 | 074.jpg | Spirited Away |
| 075 | 075.jpg | The Lion King |
| 076 | 076.jpg | WALL-E |
| 077 | 077.jpg | Toy Story |
| 078 | 078.jpg | My Neighbor Totoro |
| 079 | 079.jpg | Coco |
| 080 | 080.jpg | Finding Nemo |
| 081 | 081.jpg | Shrek |

### Horror (082-088)
| ID | Filename | Movie Title |
|---|---|---|
| 082 | 082.jpg | Get Out |
| 083 | 083.jpg | A Quiet Place |
| 084 | 084.jpg | Hereditary |
| 085 | 085.jpg | It |
| 086 | 086.jpg | The Conjuring |
| 087 | 087.jpg | Midsommar |
| 088 | 088.jpg | The Shining |

### Bollywood (089-114)
| ID | Filename | Movie Title |
|---|---|---|
| 089 | 089.jpg | 3 Idiots |
| 090 | 090.jpg | Dangal |
| 091 | 091.jpg | Dilwale Dulhania Le Jayenge |
| 092 | 092.jpg | PK |
| 093 | 093.jpg | Andhadhun |
| 094 | 094.jpg | Gully Boy |
| 095 | 095.jpg | Taare Zameen Par |
| 096 | 096.jpg | Queen |
| 097 | 097.jpg | Dil Chahta Hai |
| 098 | 098.jpg | Zindagi Na Milegi Dobara |
| 099 | 099.jpg | Barfi! |
| 100 | 100.jpg | Gangs of Wasseypur |
| 101 | 101.jpg | Uri: The Surgical Strike |
| 102 | 102.jpg | Kabir Singh |
| 103 | 103.jpg | Bajrangi Bhaijaan |
| 104 | 104.jpg | Lagaan |
| 105 | 105.jpg | Mughal-E-Azam |
| 106 | 106.jpg | Swades |
| 107 | 107.jpg | Rang De Basanti |
| 108 | 108.jpg | Dil Dhadakne Do |
| 109 | 109.jpg | Rockstar |
| 110 | 110.jpg | Kahaani |
| 111 | 111.jpg | Dil Se |
| 112 | 112.jpg | Masaan |
| 113 | 113.jpg | Article 15 |
| 114 | 114.jpg | Tumbbad |

## 🌈 Fallback Placeholder System
If a poster image is missing, the app automatically shows a **beautiful colored gradient** based on genre:
- 🎬 **Bollywood**: Orange gradient
- 🔥 **Action**: Purple-red gradient
- 💔 **Drama**: Blue gradient
- 🛸 **Sci-Fi**: Cyan-teal gradient
- 👻 **Horror**: Red-crimson gradient
- 😂 **Comedy**: Gold-yellow gradient
- ✨ **Animation**: Lavender gradient

**No broken images ever!** This means you can gradually add posters and the app still looks great.

## 🖥️ Running the Application

### Option 1: Direct Browser Access
1. Open `src/CineMatch.html` directly in your web browser
2. Application runs instantly (no server needed!)

### Option 2: Using Java Backend (Optional)
If you have the Java backend set up:
```bash
cd MovieRecommendationSystem
javac src/*.java
java -cp src Main
```

## 📥 Finding Poster Images

### Recommended Sources:
1. **IMDb** - Download official posters for each movie
2. **MoviePoster.com** - High-quality movie posters
3. **Google Images Search** - Search "[Movie Title] poster"
4. **Amazon Prime Video** - Right-click and save poster images
5. **The Movie Database (TMDB)** - tmdb.org for official artwork

### Quick Search Tips:
- Search: `"[movie title]" poster 342x513` for exact size matches
- Most movie posters are in 2:3 aspect ratio (342×513 pixels)
- JPG format is recommended for best compatibility

## ✨ Key Features with Local Posters

✅ **100% Offline** - Works without internet connection  
✅ **No API Keys Required** - Complete independence from external services  
✅ **Custom Posters** - Use any images you want  
✅ **Fast Loading** - Local files load instantly  
✅ **Beautiful Fallbacks** - Colored gradients when images are missing  
✅ **Dark & Light Mode** - Full theme support maintained  
✅ **All Features Intact** - Search, recommendations, ratings all work  

## 🚀 Quick Start Checklist

- [ ] Download movie poster images (114 total for complete coverage)
- [ ] Name them 001.jpg through 114.jpg
- [ ] Place them in `src/posters/` folder
- [ ] Open `CineMatch.html` in browser
- [ ] Test different tabs and search functionality
- [ ] Enjoy your offline movie recommendation platform!

## ❓ Troubleshooting

### Posters Not Showing
1. Check filename matches exactly (001.jpg, not 1.jpg or 001.png)
2. Verify files are in `src/posters/` folder
3. File names are **case-sensitive** on some systems
4. Try opening browser DevTools (F12) to check console for errors

### Colored Placeholders Showing
This is normal! If you haven't added a poster file yet, the app shows a beautiful colored gradient instead. Add the corresponding image file and refresh.

### Images Look Blurry
- Ensure images are at least 342×513 pixels
- Use high-quality JPG or PNG files
- Avoid heavily compressed images

## 📞 Support
If you encounter any issues:
1. Check the troubleshooting section above
2. Verify all filenames match the mapping table
3. Ensure images are in the correct folder
4. Clear browser cache and refresh (Ctrl+F5)

---

**Happy movie watching! 🍿🎬**
