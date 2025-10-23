<!DOCTYPE html>
<html lang="cs">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Jukni na to - Recepty</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0; background: #f5f5f5; color: #333; line-height: 1.6;
  }
  header {
    background: #228B22;
    color: white;
    text-align: center;
    padding: 25px 15px;
    font-size: 2.5rem;
    font-weight: 700;
    letter-spacing: 1px;
  }
  nav {
    background: white;
    text-align: center;
    padding: 10px 0;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    position: sticky;
    top: 0; z-index: 10;
  }
  nav a {
    color: #228B22;
    text-decoration: none;
    font-weight: 600;
    margin: 0 20px;
    font-size: 1.1rem;
    cursor: pointer;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #176517;
  }
  main {
    max-width: 960px;
    margin: 30px auto;
    padding: 0 15px;
  }
  h2 {
    border-bottom: 3px solid #228B22;
    padding-bottom: 8px;
    margin-bottom: 25px;
    font-weight: 700;
    font-size: 2rem;
    color: #228B22;
  }
  #searchInput {
    width: 100%;
    padding: 12px 15px;
    margin-bottom: 30px;
    font-size: 1.1rem;
    border-radius: 6px;
    border: 1px solid #ccc;
    box-shadow: inset 1px 1px 3px rgba(0,0,0,0.1);
  }
  .recept {
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    padding: 20px;
    margin-bottom: 20px;
    cursor: pointer;
    transition: transform 0.2s ease;
  }
  .recept:hover {
    transform: scale(1.03);
  }
  .recept img {
    width: 100%;
    max-height: 200px;
    object-fit: cover;
    border-radius: 6px;
    margin-bottom: 10px;
  }
  .recept h3 {
    margin: 0 0 10px 0;
    color: #228B22;
  }
  #detail {
    display: none;
    background: white;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.15);
    padding: 20px;
    margin-top: 40px;
    display: flex;
    gap: 30px;
    flex-wrap: wrap;
  }
  #detail img {
    max-width: 350px;
    width: 100%;
    border-radius: 8px;
    object-fit: cover;
    flex-shrink: 0;
  }
  #detail .text {
    flex: 1;
    min-width: 280px;
  }
  #detail h3 {
    margin-top: 0;
    color: #228B22;
  }
  #detail h4 {
    margin-bottom: 5px;
    margin-top: 20px;
    color: #176517;
  }
  #detail p {
    margin-top: 0;
    white-space: pre-line;
  }
  #detail button.closeBtn {
    background-color: #228B22;
    color: white;
    border: none;
    padding: 10px 18px;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1rem;
    margin-bottom: 15px;
    transition: background-color 0.3s ease;
  }
  #detail button.closeBtn:hover {
    background-color: #176517;
  }
  #kontaktSection {
    display: none;
    max-width: 400px;
    margin: 40px auto;
    background: white;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    text-align: center;
    color: #228B22;
    font-weight: 600;
    font-size: 1.2rem;
  }
  #kontaktSection a {
    color: #228B22;
    text-decoration: none;
    font-weight: 700;
  }
  #kontaktSection a:hover {
    text-decoration: underline;
  }
  footer {
    background: white;
    color: #228B22;
    text-align: center;
    padding: 20px 15px;
    font-size: 1rem;
    border-top: 1px solid #ddd;
    margin-top: 60px;
  }
  footer a {
    color: #228B22;
    text-decoration: none;
    font-weight: 700;
    cursor: pointer;
  }
  footer a:hover {
    text-decoration: underline;
  }
  @media (max-width: 700px) {
    #detail {
      flex-direction: column;
      align-items: center;
    }
    #detail img {
      max-width: 100%;
    }
    nav a {
      display: inline-block;
      margin: 10px 10px;
    }
  }
</style>
</head>
<body>
  <header>Jukni na to</header>
  <nav>
    <a href="#" id="linkRecepty">Recepty</a>
    <a href="#" id="linkKontakt">Kontakt</a>
  </nav>

  <main>
    <section id="receptySection">
      <h2>Vybrané recepty</h2>
      <input type="text" id="searchInput" placeholder="Hledat recept..." autocomplete="off" />
      <div id="receptyList"></div>

      <section id="detail">
        <button class="closeBtn">Zavřít detail</button>
        <img src="" alt="Detail receptu" />
        <div class="text">
          <h3></h3>
          <h4>Ingredience:</h4>
          <p id="ingredience"></p>
          <h4>Postup:</h4>
          <p id="postup"></p>
        </div>
      </section>
    </section>

    <section id="kontaktSection">
      Email: <a href="mailto:tomas.kuratko@student.zspastviny">tomas.kuratko@student.zspastviny</a>
    </section>
  </main>

  <footer>
    © 2025 Jukni na to
  </footer>

  <script>
    const receptyData = [
      {
        id: 1,
        title: "Kuřecí maso s krevetami",
        desc: "Jemné kuře s krevetami v rajčatové omáčce, podávané s rýží.",
        img: "https://www.unileverfoodsolutions.cz/dam/global-ufs/mcos/nee/czech/calcmenu/recipes/CZ-recipes/general/chow-mein-(ku%C5%99e-krevety-brokolice-mrkev)/main-header.jpg",
        ingredience: "Kuřecí prsa, krevety, rajčata, rýže, česnek, olivový olej, sůl, pepř",
        postup: "Kuře nakrájejte, krevety očistěte.\nOsmahněte česnek, přidejte kuře a krevety, poté rajčata a duste.\nPodávejte s uvařenou rýží."
      },
      {
        id: 2,
        title: "Pikantní maso s rýží",
        desc: "Ostré maso se zeleninou a rýží připravené na pánvi.",
        img: "https://varimesmozkem.cz/wp-content/uploads/2023/02/sojove-maso-cina-s-ryzi-recept.jpg",
        ingredience: "Hovězí maso, paprika, cibule, rýže, koření, olej",
        postup: "Maso nakrájejte na kousky, opečte s cibulí a paprikou, okořeňte a poduste.\nPodávejte s rýží."
      },
      {
        id: 3,
        title: "Citronové rizoto",
        desc: "Krémové rizoto s citronovou kůrou a parmazánem.",
        img: "https://images.immediate.co.uk/production/volatile/sites/53/2023/08/240820231692883316.jpeg?quality=90&resize=708,643",
        ingredience: "Rýže Arborio, citronová kůra, parmazán, máslo, cibule, bílé víno",
        postup: "Na másle osmahněte cibuli, přidejte rýži a postupně přilévejte víno a vývar.\nNakonec vmíchejte citronovou kůru a sýr."
      },
      {
        id: 4,
        title: "Lasagne",
        desc: "Těstoviny plněné masem, rajčatovou omáčkou a bešamelem.",
        img: "https://assets.tmecosys.com/image/upload/t_web_rdp_recipe_584x480_1_5x/img/recipe/ras/Assets/69EE02DA-213D-44A2-8B08-A590225B221B/Derivates/F40AD961-73B3-4E31-BC0F-A173E296F841.jpg",
        ingredience: "Těstoviny na lasagne, mleté maso, rajčatová omáčka, bešamel, sýr",
        postup: "Vrství těstoviny, maso a omáčky, zakončete sýrem a zapečte v troubě."
      },
      {
        id: 5,
        title: "Pečené kuře s rozmarýnem",
        desc: "Šťavnaté pečené kuře s bylinkami a zeleninou.",
        img: "https://kuchynelidlu.cz/productFiles/7837/1-KW-03-23-beautyshot-Pecene-kureci-stehno-na-rozmarynu-s-houbovou-pohankou-1132x637.jpeg",
        ingredience: "Kuře, rozmarýn, česnek, zelenina, olej, sůl, pepř",
        postup: "Kuře potřete kořením, pečte s bylinkami a zeleninou do zlatova."
      },
      {
        id: 6,
        title: "Špagety carbonara",
        desc: "Klasické špagety s vajíčky, slaninou a sýrem.",
        img: "https://cdn.rohlik.cz/images/meals/large/1869-1630062843692.jpg",
        ingredience: "Špagety, vajíčka, parmazán, slanina, pepř",
        postup: "Uvařte špagety, smíchejte s osmaženou slaninou a vajíčkovou směsí.\nDochutťe sýrem a pepřem."
      },
      {
        id: 7,
        title: "Kari zelenina s rýží",
        desc: "Vegetariánské kari s kokosovým mlékem a rýží.",
        img: "https://kaufland.media.schwarz/is/image/schwarz/recipe-cz-10149721_social-ryze-kari-zelenina-veprove-maso:k-smartcrop-og-1354",
        ingredience: "Kari pasta, kokosové mléko, cuketa, paprika, rýže",
        postup: "Na pánvi osmahněte zeleninu, přidejte kari pastu a kokosové mléko.\nDuste do změknutí. Podávejte s rýží."
      },
      {
        id: 8,
        title: "Tradiční guláš",
        desc: "Hovězí guláš s knedlíky, ideální české jídlo.",
        img: "https://cdn.myshoptet.com/usr/www.chut.cz/user/documents/upload/gulas_3.jpg",
        ingredience: "Hovězí maso, cibule, paprika, česnek, kmín, mouka, vývar",
        postup: "Maso osmahněte s cibulí a paprikou, přidejte koření a vývar.\nDuste do měkka. Podávejte s knedlíky."
      }
    ];

    const receptyList = document.getElementById('receptyList');
    const detailSection = document.getElementById('detail');
    const detailImg = detailSection.querySelector('img');
    const detailTitle = detailSection.querySelector('h3');
    const ingredienceP = document.getElementById('ingredience');
    const postupP = document.getElementById('postup');
    const closeBtn = detailSection.querySelector('.closeBtn');
    const searchInput = document.getElementById('searchInput');
    const linkKontakt = document.getElementById('linkKontakt');
    const linkRecepty = document.getElementById('linkRecepty');
    const kontaktSection = document.getElementById('kontaktSection');
    const receptySection = document.getElementById('receptySection');

    function vykresliRecepty(filterText = '') {
      receptyList.innerHTML = '';
      const filtered = receptyData.filter(r => {
        const fullText = (r.title + ' ' + r.desc).toLowerCase();
        return fullText.includes(filterText.toLowerCase());
      });

      if(filtered.length === 0) {
        receptyList.innerHTML = '<p>Žádné recepty neodpovídají hledání.</p>';
        detailSection.style.display = 'none';
        return;
      }

      filtered.forEach(r => {
        const cl = document.createElement('div');
        cl.classList.add('recept');
        cl.setAttribute('data-id', r.id);
        cl.innerHTML = `<img src="${r.img}" alt="${r.title}" /><h3>${r.title}</h3><p>${r.desc}</p>`;
        cl.addEventListener('click', () => zobrazDetail(r.id));
        receptyList.appendChild(cl);
      });
      detailSection.style.display = 'none';
    }

    function zobrazDetail(id) {
      const recept = receptyData.find(r => r.id === id);
      if(!recept) return;
      detailImg.src = recept.img;
      detailImg.alt = recept.title;
      detailTitle.textContent = recept.title;
      ingredienceP.textContent = recept.ingredience;
      postupP.textContent = recept.postup;
      detailSection.style.display = 'flex';
      detailSection.scrollIntoView({behavior: 'smooth'});
    }

    closeBtn.addEventListener('click', () => {
      detailSection.style.display = 'none';
    });

    searchInput.addEventListener('input', () => {
      const val = searchInput.value.trim();
      vykresliRecepty(val);
    });

    linkKontakt.addEventListener('click', e => {
      e.preventDefault();
      kontaktSection.style.display = 'block';
      receptySection.style.display = 'none';
    });

    linkRecepty.addEventListener('click', e => {
      e.preventDefault();
      kontaktSection.style.display = 'none';
      receptySection.style.display = 'block';
    });

    vykresliRecepty();
  </script>
</body>
</html>
