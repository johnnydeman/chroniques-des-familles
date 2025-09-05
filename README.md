[index.html](https://github.com/user-attachments/files/22182211/index.html)
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chroniques des Familles Deman – Lebon – Wauthy – Borny – de Namur</title>
    <!-- Meta SEO tags -->
    <meta name="description" content="Découvrez les chroniques des familles Deman, Lebon, Wauthy, Borny et de Namur : une histoire familiale riche en terres, mer, drames et noblesse, des fermes de Flandre aux châteaux du Hainaut.">
    <meta name="keywords" content="généalogie, famille Deman, famille Lebon, famille Wauthy, famille Borny, famille de Namur, histoire familiale, Flandre, Hainaut, chroniques familiales">
    <meta name="author" content="Chroniques des Familles">
    <meta name="robots" content="index, follow">
    <meta name="googlebot" content="index, follow">
    <meta name="bingbot" content="index, follow">
    <!-- Open Graph for social sharing -->
    <meta property="og:type" content="website">
    <meta property="og:title" content="Chroniques des Familles Deman – Lebon – Wauthy – Borny – de Namur">
    <meta property="og:description" content="Une plongée dans l’histoire des familles Deman, Lebon, Wauthy, Borny et de Namur mêlant terre, mer, drame et noblesse.">
    <meta property="og:locale" content="fr_FR">
    <link rel="canonical" href="https://johnnydeman.github.io/chroniques-des-familles/">
    <meta property="og:url" content="https://johnnydeman.github.io/chroniques-des-familles/">
    <!-- FontAwesome & Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://cdnjs.cloudflare.com">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-zSM9gnLUo86mQqqF1zCkFZi+CL/CwDCf8IkgkLhtQhlnCDZzOIvGaW4ab9rT9uQHr0PwC+CwAlum9FFdJ7BrMg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* Card shadow and hover effect */
        .family-card {
            transition: all 0.3s ease;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .family-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }
        /* Timeline dots and line */
        .timeline-item::before {
            content: '';
            position: absolute;
            left: -38px;
            top: 0;
            width: 20px;
            height: 20px;
            border-radius: 50%;
            background: #4f46e5;
        }
        .timeline::before {
            content: '';
            position: absolute;
            left: 33px;
            top: 0;
            height: 100%;
            width: 2px;
            background: #e5e7eb;
        }
        @media (max-width: 768px) {
            .timeline::before {
                left: 18px;
            }
            .timeline-item::before {
                left: -28px;
                width: 15px;
                height: 15px;
            }
        }
    </style>
    <!-- Audio object structured data -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "AudioObject",
      "name": "Saga familiale Deman – Lebon – Wauthy – Borny – de Namur",
      "description": "Récit audio de la généalogie familiale, des fermes de Flandre aux châteaux du Hainaut.",
      "encodingFormat": "audio/mpeg",
      "contentUrl": "https://johnnydeman.github.io/chroniques-des-familles/audio/saga.mp3",
      "author": { "@type": "Person", "name": "Johnny Deman" },
      "inLanguage": "fr"
    }
    </script>
</head>
<body class="bg-gray-50 font-serif">
    <header class="bg-gradient-to-r from-indigo-900 to-purple-900 text-white py-12 px-4">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Chroniques des Familles</h1>
            <nav aria-label="familles" class="flex flex-wrap justify-center gap-2 md:gap-4 mt-6">
                <span class="bg-indigo-700 px-3 py-1 rounded-full text-sm md:text-base">Deman</span>
                <span class="bg-purple-700 px-3 py-1 rounded-full text-sm md:text-base">Lebon</span>
                <span class="bg-blue-700 px-3 py-1 rounded-full text-sm md:text-base">Wauthy</span>
                <span class="bg-teal-700 px-3 py-1 rounded-full text-sm md:text-base">Borny</span>
                <span class="bg-amber-700 px-3 py-1 rounded-full text-sm md:text-base">de Namur</span>
                <a href="#saga-familiale" class="bg-pink-700 px-3 py-1 rounded-full text-sm md:text-base">Audio</a>
            </nav>
        </div>
    </header>

    <main class="container mx-auto px-4 py-12 max-w-6xl">
        <!-- Introduction -->
        <section class="mb-16">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">Une Histoire Riche et Complexe</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">
                    Ces chroniques familiales révèlent une histoire où s'entremêlent la terre, la mer, le drame et la noblesse,
                    des fermes de Flandre aux châteaux du Hainaut.
                </p>
            </div>

            <!-- Family summary cards -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 mb-12">
                <!-- Famille Deman -->
                <article class="family-card bg-white rounded-lg overflow-hidden border border-gray-200" itemscope itemtype="https://schema.org/Person">
                    <header class="bg-indigo-800 p-4 text-white">
                        <h3 class="text-xl font-bold" itemprop="name"><i class="fas fa-tractor mr-2" aria-hidden="true"></i> Famille Deman</h3>
                        <p class="text-indigo-200">Laboureurs, terrassiers et aubergistes</p>
                    </header>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4" itemprop="description">Originaire de Mannekensvere (Flandre-Occidentale), marquée par les drames de guerre et les accidents tragiques.</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fas fa-map-marker-alt mr-2" aria-hidden="true"></i>
                            <span itemprop="addressLocality">Mannekensvere, Middelkerke</span>
                        </div>
                    </div>
                </article>

                <!-- Famille Borny -->
                <article class="family-card bg-white rounded-lg overflow-hidden border border-gray-200" itemscope itemtype="https://schema.org/Person">
                    <header class="bg-teal-800 p-4 text-white">
                        <h3 class="text-xl font-bold" itemprop="name"><i class="fas fa-wind mr-2" aria-hidden="true"></i> Famille Borny</h3>
                        <p class="text-teal-200">Entre moulin et mer</p>
                    </header>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4" itemprop="description">Implantée à Klemskerke et De Haan, avec une destinée maritime tragique marquée par des naufrages.</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fas fa-map-marker-alt mr-2" aria-hidden="true"></i>
                            <span itemprop="addressLocality">Klemskerke, De Haan, Vosseslag</span>
                        </div>
                    </div>
                </article>

                <!-- Famille Lebon -->
                <article class="family-card bg-white rounded-lg overflow-hidden border border-gray-200" itemscope itemtype="https://schema.org/Person">
                    <header class="bg-purple-800 p-4 text-white">
                        <h3 class="text-xl font-bold" itemprop="name"><i class="fas fa-leaf mr-2" aria-hidden="true"></i> Famille Lebon</h3>
                        <p class="text-purple-200">Cultivateurs et journaliers</p>
                    </header>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4" itemprop="description">Originaire de Fleurus, Ligny, Brye et Marbais, avec une stabilité paysanne et des alliances régionales.</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fas fa-map-marker-alt mr-2" aria-hidden="true"></i>
                            <span itemprop="addressLocality">Fleurus, Ligny, Brye, Marbais</span>
                        </div>
                    </div>
                </article>

                <!-- Famille Wauthy -->
                <article class="family-card bg-white rounded-lg overflow-hidden border border-gray-200" itemscope itemtype="https://schema.org/Person">
                    <header class="bg-blue-800 p-4 text-white">
                        <h3 class="text-xl font-bold" itemprop="name"><i class="fas fa-landmark mr-2" aria-hidden="true"></i> Famille Wauthy</h3>
                        <p class="text-blue-200">Notables du Brabant et du Namurois</p>
                    </header>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4" itemprop="description">La branche la plus ancienne et prestigieuse, documentée dès le XVIe siècle, avec des fonctions importantes.</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fas fa-map-marker-alt mr-2" aria-hidden="true"></i>
                            <span itemprop="addressLocality">Houtain-le-Val, Rèves, Sart-Dames-Avelines</span>
                        </div>
                    </div>
                </article>

                <!-- Famille de Namur -->
                <article class="family-card bg-white rounded-lg overflow-hidden border border-gray-200" itemscope itemtype="https://schema.org/Person">
                    <header class="bg-amber-800 p-4 text-white">
                        <h3 class="text-xl font-bold" itemprop="name"><i class="fas fa-crown mr-2" aria-hidden="true"></i> Famille de Namur</h3>
                        <p class="text-amber-200">Lignée noble médiévale</p>
                    </header>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4" itemprop="description">Rattachement à la maison capétienne et carolingienne, aux seigneurs du Hainaut et de Namur.</p>
                        <div class="flex items-center text-sm text-gray-500">
                            <i class="fas fa-map-marker-alt mr-2" aria-hidden="true"></i>
                            <span itemprop="addressLocality">Trivières, Rianwelz, Hainaut</span>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- Audio saga section -->
        <section id="saga-familiale" class="bg-white rounded-lg shadow-md p-6 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-4 text-center">🎧 Saga familiale (audio)</h2>
            <div class="max-w-3xl mx-auto">
                <audio controls preload="none" class="w-full rounded-lg">
                    <source src="audio/saga.mp3" type="audio/mpeg">
                    Votre navigateur ne supporte pas l’audio. <a href="audio/saga.mp3" download>Télécharger</a>.
                </audio>
                <div class="mt-4 flex flex-wrap gap-3">
                    <a href="audio/saga.mp3" download class="inline-flex items-center px-4 py-2 rounded-lg bg-indigo-600 text-white hover:bg-indigo-700">
                        ⬇️ Télécharger l’audio (MP3)
                    </a>
                    <button onclick="document.getElementById('transcription').open = true" class="inline-flex items-center px-4 py-2 rounded-lg bg-gray-100 hover:bg-gray-200 text-gray-800">
                        📝 Afficher la transcription
                    </button>
                </div>
                <details id="transcription" class="mt-6">
                    <summary class="cursor-pointer text-lg font-semibold text-gray-800">Transcription complète</summary>
                    <div class="prose max-w-none text-gray-700 mt-3">
                        <p><em>(Quand tu veux, tu me l’envoies et je colle ici la version propre — excellent pour le SEO.)</em></p>
                    </div>
                </details>
            </div>
        </section>

        <!-- Details sections -->
        <section class="mb-16">
            <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Détails des Familles</h2>
            
            <!-- Famille Deman details -->
            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-12" itemscope itemtype="https://schema.org/Person">
                <header class="bg-indigo-800 p-4 text-white">
                    <h3 class="text-2xl font-bold" itemprop="name">1. La famille Deman</h3>
                </header>
                <div class="p-6">
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Origines</h4>
                        <p class="text-gray-700" itemprop="description">
                            Originaire de Mannekensvere (Flandre-Occidentale), les Deman sont d'abord des laboureurs, terrassiers et aubergistes.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Théophiel Florimond Deman (1872–1946)</h4>
                        <p class="text-gray-700 mb-4">
                            Cultivateur et petit commerçant. Époux d'Urbanie Baeckelandt, il donna naissance à une descendance marquée par les drames.
                        </p>
                        <div class="pl-6 border-l-4 border-indigo-200">
                            <h5 class="font-semibold text-gray-800">Enfants :</h5>
                            <ul class="list-disc pl-5 text-gray-700 space-y-2 mt-2">
                                <li><span class="font-medium">Léon Seraphin Deman (1899–1970)</span> - Vétéran de la Première Guerre mondiale, y perdit un œil et porta un œil de verre toute sa vie. Figure populaire de Middelkerke.</li>
                                <li><span class="font-medium">Amatus "Aimé" Deman (1901–1935)</span> - Garde-chasse, assassiné par un braconnier.</li>
                                <li><span class="font-medium">Karel Deman (1907–1947)</span> - Mort jeune lors d'une course cycliste.</li>
                            </ul>
                        </div>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Première Guerre mondiale</h4>
                        <p class="text-gray-700">
                            Pendant la Première Guerre mondiale, le village de Mannekensvere et toute la vallée environnante furent délibérément inondés par l'armée belge. En octobre 1914, pour stopper l'avance allemande, on ouvrit les écluses de Nieuport. Les plaines de l'Yser furent submergées durant quatre années entières.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Descendance</h4>
                        <p class="text-gray-700">
                            La descendance se poursuit par Odette Deman, fille d'Aimé, qui donna naissance à Jean-Marie Deman (1947–2014), époux d'Annie Lebon. Jean-Marie mourut tragiquement en 2014 dans les inondations des Pyrénées, emporté par la rivière.
                        </p>
                    </section>
                </div>
            </article>

            <!-- Famille Borny details -->
            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-12" itemscope itemtype="https://schema.org/Person">
                <header class="bg-teal-800 p-4 text-white">
                    <h3 class="text-2xl font-bold" itemprop="name">2. La famille Borny</h3>
                </header>
                <div class="p-6">
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Origines</h4>
                        <p class="text-gray-700" itemprop="description">
                            Implantée à Klemskerke et De Haan, la famille Borny vécut entre moulin et mer.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Charles Louis Borny (†1911)</h4>
                        <p class="text-gray-700">
                            Propriétaire du moulin dit Borny Molen. Sa mort prématurée laissa le moulin à sa veuve et enfants.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Tragédies maritimes</h4>
                        <p class="text-gray-700 mb-4">
                            Frans Borny (1911–1929) et Ingelbrechtus Borny (1889–1929) périrent dans un naufrage au large de Vosseslag, un épisode qui marqua la mémoire locale.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Lien avec les Deman</h4>
                        <p class="text-gray-700">
                            Michel/Marcel Borny (vers 1910) aurait été le père naturel de Jean-Marie Deman, reliant ainsi les Borny aux Deman.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Conclusion</h4>
                        <p class="text-gray-700">
                            Les Borny incarnent la destinée maritime : la terre par le moulin, la mer par le drame.
                        </p>
                    </section>
                </div>
            </article>

            <!-- Famille Lebon details -->
            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-12" itemscope itemtype="https://schema.org/Person">
                <header class="bg-purple-800 p-4 text-white">
                    <h3 class="text-2xl font-bold" itemprop="name">3. La famille Lebon</h3>
                </header>
                <div class="p-6">
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Origines</h4>
                        <p class="text-gray-700">
                            Originaire de Fleurus, Ligny, Brye et Marbais, les Lebon sont d'abord des cultivateurs et journaliers.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Ascendance</h4>
                        <div class="pl-6 border-l-4 border-purple-200">
                            <ul class="list-disc pl-5 text-gray-700 space-y-2">
                                <li><span class="font-medium">François Charles Lebon (1624, Fleurus)</span> - Premier ancêtre identifié.</li>
                                <li>Ses descendants passent par <span class="font-medium">Pierre Joseph Lebon (1745)</span> → <span class="font-medium">Charles Joseph Lebon (1824)</span> → <span class="font-medium">Olivier Joseph Lebon (1859)</span>.</li>
                                <li><span class="font-medium">Joseph Jean Robert Lebon (1917–1960)</span> - Né à Rouen, revient en Belgique et s'établit à Brye avec Paula Wauthy (1919–2008).</li>
                                <li>Leur fille <span class="font-medium">Annie Lebon (1953)</span> épousa Jean-Marie Deman.</li>
                            </ul>
                        </div>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Caractéristiques</h4>
                        <p class="text-gray-700">
                            La lignée Lebon, moins dramatique, se distingue par une stabilité paysanne et des alliances dans la région de Fleurus. Ligny et Marbais
                        </p>
                    </section>
                </div>
            </article>

            <!-- Famille Wauthy details -->
            <article class="bg-white rounded-lg shadow-md overflow-hidden mb-12" itemscope itemtype="https://schema.org/Person">
                <header class="bg-blue-800 p-4 text-white">
                    <h3 class="text-2xl font-bold" itemprop="name">4. La famille Wauthy</h3>
                </header>
                <div class="p-6">
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Origines</h4>
                        <p class="text-gray-700">
                            C'est la branche la plus ancienne et prestigieuse, documentée dès le XVIe siècle.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Personnages marquants</h4>
                        <div class="pl-6 border-l-4 border-blue-200">
                            <ul class="list-disc pl-5 text-gray-700 space-y-2">
                                <li><span class="font-medium">Jean II Wauthy (1605–1660)</span> - Mayeur d'Houtain-le-Val et de Rèves, lieutenant-bailli, représente l'ascension d'une famille de notables.</li>
                                <li>Son fils <span class="font-medium">Pierre Philippe Wauthy (1632–1715)</span> devient prêtre-curé de Sart-Dames-Avelines et de Baulers.</li>
                                <li><span class="font-medium">Armand Joseph Wauthy (1805–1885)</span> - Cultivateur de Wagnelée, assure la continuité familiale.</li>
                            </ul>
                        </div>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Alliances</h4>
                        <p class="text-gray-700 mb-2">
                            Marie Jacquet (1633–1702), issue de la lignée de Becquevort (ancienne noblesse de Grand-Leez). Familles Vassart, Labart, Hainaut.
                        </p>
                        <p class="text-gray-700">
                            La descendance directe : Paula Wauthy (1919–2008), épouse de Joseph Lebon, rattache cette noblesse aux générations actuelles.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Conclusion</h4>
                        <p class="text-gray-700">
                            Les Wauthy illustrent un parcours typique des notables du Brabant et du Namurois.
                        </p>
                    </section>
                </div>
            </article>

            <!-- Famille de Namur details -->
            <article class="bg-white rounded-lg shadow-md overflow-hidden" itemscope itemtype="https://schema.org/Person">
                <header class="bg-amber-800 p-4 text-white">
                    <h3 class="text-2xl font-bold" itemprop="name">5. La famille de Namur</h3>
                </header>
                <div class="p-6">
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Origines</h4>
                        <p class="text-gray-700">
                            C'est la lignée noble qui relie indirectement les Wauthy-Jacquet à l'histoire médiévale.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Marie de Namur (1523–1603)</h4>
                        <p class="text-gray-700">
                            Dame de Trivières et Rianwelz, épousa Jacques (Jean II) de La Hamaide.
                        </p>
                    </section>
                    
                    <section class="mb-6">
                        <h4 class="text-xl font-semibold text-gray-800 mb-3">Descendance et alliances</h4>
                        <p class="text-gray-700 mb-2">
                            Leur descendance s'unit avec les de Becquevort, puis avec les Jacquet, puis les Wauthy.
                        </p>
                        <p class="text-gray-700">
                            Ce fil généalogique rattache la famille à la maison capétienne et carolingienne, aux seigneurs du Hainaut et de Namur, et à des lignées médiévales prestigieuses (Savoie, Bourgogne, Rollon de Normandie, Charlemagne).
                        </p>
                    </section>
                </div>
            </article>
        </section>

        <!-- Family tree timeline -->
        <section class="bg-white rounded-lg shadow-md p-6 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 text-center">Arbre Généalogique Simplifié</h2>
            <div class="overflow-x-auto">
                <div class="min-w-max">
                    <div class="flex justify-center">
                        <div class="relative timeline pl-12">
                            <!-- de Namur node -->
                            <div class="timeline-item relative pb-10">
                                <div class="bg-indigo-100 border border-indigo-200 rounded-lg p-4" role="group" aria-label="Famille de Namur">
                                    <h4 class="font-bold text-indigo-800">Famille de Namur</h4>
                                    <p class="text-sm text-gray-600">Marie de Namur (1523–1603)</p>
                                </div>
                            </div>
                            <!-- Wauthy node -->
                            <div class="timeline-item relative pb-10">
                                <div class="bg-blue-100 border border-blue-200 rounded-lg p-4" role="group" aria-label="Famille Wauthy">
                                    <h4 class="font-bold text-blue-800">Famille Wauthy</h4>
                                    <p class="text-sm text-gray-600">Jean II Wauthy (1605–1660)</p>
                                </div>
                            </div>
                            <!-- Lebon node -->
                            <div class="timeline-item relative pb-10">
                                <div class="bg-purple-100 border border-purple-200 rounded-lg p-4" role="group" aria-label="Famille Lebon">
                                    <h4 class="font-bold text-purple-800">Famille Lebon</h4>
                                    <p class="text-sm text-gray-600">Joseph Lebon (1917–1960) + Paula Wauthy (1919–2008)</p>
                                </div>
                            </div>
                            <!-- Borny node -->
                            <div class="timeline-item relative pb-10">
                                <div class="bg-teal-100 border border-teal-200 rounded-lg p-4" role="group" aria-label="Famille Borny">
                                    <h4 class="font-bold text-teal-800">Famille Borny</h4>
                                    <p class="text-sm text-gray-600">Michel/Marcel Borny (vers 1910)</p>
                                </div>
                            </div>
                            <!-- Deman node -->
                            <div class="timeline-item relative">
                                <div class="bg-indigo-100 border border-indigo-200 rounded-lg p-4" role="group" aria-label="Famille Deman">
                                    <h4 class="font-bold text-indigo-800">Famille Deman</h4>
                                    <p class="text-sm text-gray-600">Jean-Marie Deman (1947–2014) + Annie Lebon (1953)</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Conclusion section -->
        <section class="bg-gradient-to-r from-indigo-900 to-purple-900 text-white rounded-lg shadow-lg p-8">
            <h2 class="text-3xl font-bold mb-6 text-center">Conclusion</h2>
            <div class="max-w-3xl mx-auto">
                <p class="text-lg mb-6">
                    Les chroniques croisées des Deman, Borny, Lebon, Wauthy et de Namur révèlent une histoire riche où s'entremêlent :
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 mb-8">
                    <div class="bg-white bg-opacity-10 p-4 rounded-lg">
                        <div class="flex items-center mb-2">
                            <i class="fas fa-tractor text-2xl mr-3" aria-hidden="true"></i>
                            <h4 class="text-xl font-semibold">La terre</h4>
                        </div>
                        <p class="text-indigo-100">(cultivateurs, censiers)</p>
                    </div>
                    <div class="bg-white bg-opacity-10 p-4 rounded-lg">
                        <div class="flex items-center mb-2">
                            <i class="fas fa-water text-2xl mr-3" aria-hidden="true"></i>
                            <h4 class="text-xl font-semibold">La mer</h4>
                        </div>
                        <p class="text-indigo-100">(naufrages, pêche)</p>
                    </div>
                    <div class="bg-white bg-opacity-10 p-4 rounded-lg">
                        <div class="flex items-center mb-2">
                            <i class="fas fa-exclamation-triangle text-2xl mr-3" aria-hidden="true"></i>
                            <h4 class="text-xl font-semibold">Le drame</h4>
                        </div>
                        <p class="text-indigo-100">(meurtres, accidents, guerres)</p>
                    </div>
                    <div class="bg-white bg-opacity-10 p-4 rounded-lg">
                        <div class="flex items-center mb-2">
                            <i class="fas fa-crown text-2xl mr-3" aria-hidden="true"></i>
                            <h4 class="text-xl font-semibold">La noblesse</h4>
                        </div>
                        <p class="text-indigo-100">(alliances médiévales)</p>
                    </div>
                </div>
                <p class="text-lg">
                    Cette mosaïque fait de votre généalogie une histoire familiale complète, allant des fermes de Flandre aux châteaux du Hainaut, des moulins de Klemskerke aux rivières tragiques des Pyrénées.
                </p>
            </div>
        </section>
    </main>

    <!-- Footer with social links -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-4 text-center">
            <p class="mb-4">© 2025 Chroniques des Familles Deman – Lebon – Wauthy – Borny – de Namur</p>
            <ul class="flex justify-center space-x-4" aria-label="Réseaux sociaux">
                <li><a href="#" class="hover:text-indigo-300" aria-label="Facebook"><i class="fab fa-facebook-f" aria-hidden="true"></i></a></li>
                <li><a href="#" class="hover:text-indigo-300" aria-label="Twitter"><i class="fab fa-twitter" aria-hidden="true"></i></a></li>
                <li><a href="#" class="hover:text-indigo-300" aria-label="Instagram"><i class="fab fa-instagram" aria-hidden="true"></i></a></li>
                <li><a href="#" class="hover:text-indigo-300" aria-label="Email"><i class="fas fa-envelope" aria-hidden="true"></i></a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
