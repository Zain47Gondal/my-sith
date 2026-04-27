.quality-tag {
            position: absolute;
            top: 10px;
            left: 10px;
            background: var(--primary-color);
            font-size: 10px;
            padding: 2px 6px;
            border-radius: 3px;
        }

        .card-info {
            padding: 10px;
            text-align: center;
        }

        .card-info h3 {
            font-size: 13px;
            color: #ddd;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: #000;
            border-top: 1px solid #222;
            margin-top: 50px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .header-content {
                flex-direction: column;
                text-align: center;
            }
            nav ul {
                gap: 10px;
                flex-wrap: wrap;
                justify-content: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="container header-content">
            <div class="logo">
                <h1>Madam <span>Ji</span></h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">Bollywood</a></li>
                    <li><a href="#">Hollywood</a></li>
                    <li><a href="#">Web Series</a></li>
                </ul>
            </nav>
            <div class="search-box">
                <input type="text" placeholder="Search movies...">
                <button>Go</button>
            </div>
        </div>
    </header>

    <main class="container">
        
        <section class="main-player">
            <div class="video-container">
                <video id="madam-ji-player" class="video-js vjs-big-play-centered vjs-16-9" controls preload="auto" poster="https://via.placeholder.com/800x450/000/fff?text=Madam+Ji+Player">
                    <source src="YOUR_DIRECT_VIDEO_LINK_HERE.mp4" type="video/mp4" />
                </video>
            </div>
            <div class="player-info">
                <h2>Currently Watching: Movie Title 2026</h2>
                <div class="server-list">
                    <span class="server-btn active">Ad-Free Server</span>
                    <span class="server-btn">Backup HD</span>
                </div>
            </div>
        </section>

        <h2 class="section-title">Trending Now</h2>
        <div class="grid">
            <div class="card">
                <span class="quality-tag">1080p</span>
                <img src="https://via.placeholder.com/200x300" alt="Movie">
                <div class="card-info">
                    <h3>The Dark Night (2024) Hindi</h3>
                </div>
            </div>
            <div class="card">
                <span class="quality-tag">WEB-DL</span>
                <img src="https://via.placeholder.com/200x300" alt="Movie">
                <div class="card-info">
                    <h3>Action Series S01 (Dual Audio)</h3>
                </div>
            </div>
            <div class="card">
                <span class="quality-tag">HDRip</span>
                <img src="https://via.placeholder.com/200x300" alt="Movie">
                <div class="card-info">
                    <h3>Romantic Comedy (2024)</h3>
                </div>
            </div>
            <div class="card">
                <span class="quality-tag">720p</span>
                <img src="https://via.placeholder.com/200x300" alt="Movie">
                <div class="card-info">
                    <h3>Sci-Fi Adventure (2023)</h3>
                </div>
            </div>
        </div>

    </main>

    <footer>
        <p>&copy; 2026 Madam Ji. Quality Movies without Ads.</p>
    </footer>

    <script src="https://vjs.zencdn.net/8.10.0/video.min.js"></script>
</body>
</html>
