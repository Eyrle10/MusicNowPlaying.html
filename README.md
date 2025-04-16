# MusicNowPlaying.html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Musify</title>

    <link rel="icon" type="image/png" href="image/musify-logo.png">

    <link rel="stylesheet" href="MusicPlaylist.css">

</head>

<body>

    <video autoplay loop muted plays-inline class="backgroundv">

        <source src="image/video.mp4" type="video/mp4">

    </video>

    <div class="header">

        <span>Musify</span>

        <input type="text" placeholder="Search">

        <div class="right-section">

            <a href="Chats.html" style="color: white; text-decoration: none;"><span><img class="Chats" src="image/Chats.png">Chats</span></a>

            <span><img class="notif" src="image/notification.png">Notifications</span>

            <a href="MusicAboutUs.html" style="color: white; text-decoration: none;"><span><img class="About" src="image/about us.png">About Us</span></a>

            <a href="MusicLogin.html" style="color: white; text-decoration: none;"><span><img class="Account" src="image/account.png"> Account</span></a>

        </div>

    </div>

    <div class="sidebar">

        <div class="itemss">

            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><img class="icon" src="image/home.png"></a>

            <a href="MusicHomePage.html" style="color: white; text-decoration: none;"><div class="texts">Home</div></a>

        </div>

        <div class="itemss">

            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><img class="icon" src="image/playlists.png"></a>

            <a href="MusicPlaylists.html" style="color: white; text-decoration: none;"><div class="texts">Playlists</div></a>

        </div>

        <div class="itemss">

            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><img class="icon" src="image/favorites.png"></a>

            <a href="MusicFavorites.html" style="color: white; text-decoration: none;"><div class="texts">Favorites</div></a>

        </div>

        <div class="itemss">

            <img class="icon" class="active" src="image/now playing.png">

            <div class="texts" class="active">Now Playing</div>

        </div>

        <div class="itemss">

            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><img class="icon" src="image/recently played.png"></a>

            <a href="MusicRecentlyPlayed.html" style="color: white; text-decoration: none;"><div class="texts">Recently Played</div></a>

        </div>

        <div class="itemss">

            <img class="icon" src="image/settings.png">

            <div class="texts">Settings</div>

        </div>

        <a href="MusicLogin.html" style="color: white; text-decoration: none;"><div class="itemss">

            <img class="icon" src="image/logout.png">

            <div class="texts">Logout</div>

        </div></a>

    </div>

    <div class="main-content">

        <h1 style="color: white; text-decoration: none;">best of 2020’s</h1>

        <div class="now-playing">

            <img src="image/music.jpg" alt="Album Cover">

            <marquee behavior="scroll" direction="left" scrollamount="7"> <h3>SAMPLE TITLE</h3></marquee>

            <p>ARTIST</p>

            <input type="range" id="progress" value="0" max="100" step="0.1">

            <span id="current-time">0:00</span> / <span id="duration">0:00</span>

            <div class="controls">

                <button>&#8634;</button>

                <button>⏮</button>

                <button>▶</button>

                <button>⏭</button>

            </div>

        </div>

    </div>

    <div class="playlist">

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>BAHIAN song's</h4></marquee>

                        <p>BAHIAN</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>DIZON song's</h4></marquee>

                        <p>DIZON</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>PAMISA song's</h4></marquee>

                        <p>PAMISA</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SABUERO song's</h4></marquee>

                        <p>SABUERO</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALIGUMBA song's</h4></marquee>

                        <p>SALIGUMBA</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SALINAS song's</h4></marquee>

                        <p>SALINAS</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SANTARITA song's</h4></marquee>

                        <p>SANTARITA</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

                <div class="song">

                    <img src="image/music.jpg" alt="Album">

                    <div class="info">

                        <marquee behavior="scroll" direction="left" scrollamount="7"> <h4>SAMPLE TITLE</h4></marquee>

                        <p>ARTIST</p>

                    </div>

                    <button>&#9654;</button>

                </div>

            </div>

</body>

  </html>
