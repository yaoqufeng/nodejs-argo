<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>中华本草：名贵药材图鉴 | Herb Atlas of China</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;700&family=Ma+Shan+Zheng&display=swap" rel="stylesheet">
    <style>
        :root {
            --herb-green: #2d4635; 
            --paper-color: #fcfaf2; 
            --gold: #b8860b;
            --accent-red: #8b0000; 
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { 
            font-family: 'Noto Serif SC', serif; 
            line-height: 1.6; 
            color: #333; 
            background-color: #e5e5e5; 
            background-image: url('https://www.transparenttextures.com/patterns/parchment.png');
            overflow: hidden;
        }

        header { 
            background-color: var(--herb-green); 
            border-bottom: 3px solid var(--gold);
            position: fixed; width: 100%; z-index: 1000; 
            box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        }
        nav { 
            max-width: 1600px; margin: 0 auto; 
            display: flex; justify-content: space-between; align-items: center; 
            padding: 10px 30px; 
        }
        .logo-text { font-size: 26px; font-weight: 700; color: var(--paper-color); font-family: 'Ma Shan Zheng', cursive; }
        .logo-text span { font-size: 14px; font-family: 'Noto Serif SC'; margin-left: 10px; opacity: 0.8; font-weight: 400; }

        .main-explorer {
            display: grid;
            grid-template-columns: 1.6fr 1fr;
            gap: 25px;
            padding: 100px 30px 30px;
            max-width: 1800px; margin: 0 auto;
            height: 100vh;
        }

        /* 地图区：使用您指定的木质地图链接 */
        .map-container {
            position: relative;
            background-color: #d2b48c;
            background-image: url('https://i.etsystatic.com/21069375/r/il/b09bf1/3788054865/il_794xN.3788054865_fms1.jpg');
            background-size: 100% 100%;
            background-repeat: no-repeat;
            background-position: center;
            border-radius: 15px;
            border: 8px solid #fff;
            box-shadow: 0 20px 50px rgba(0,0,0,0.3);
            overflow: hidden;
        }

        .pin {
            position: absolute;
            width: 18px; height: 18px;
            background: var(--accent-red);
            border: 2px solid white;
            border-radius: 50%;
            cursor: pointer;
            transform: translate(-50%, -50%);
            z-index: 10;
            transition: 0.3s;
            box-shadow: 0 0 15px var(--accent-red);
        }
        .pin::after {
            content: ''; position: absolute; width: 100%; height: 100%;
            border-radius: 50%; background: var(--accent-red);
            animation: pulse 2.5s infinite;
        }
        .pin:hover, .pin.active {
            background: var(--gold);
            transform: translate(-50%, -50%) scale(1.8);
            box-shadow: 0 0 25px var(--gold);
            z-index: 100;
        }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 0.8; }
            100% { transform: scale(3.5); opacity: 0; }
        }

        /* 基于您提供的图片比例精调坐标 */
        .p-ginseng    { top: 20%; left: 83%; } /* 吉林人参 */
        .p-cordyceps  { top: 58%; left: 34%; } /* 西藏冬虫夏草 */
        .p-goji       { top: 38%; left: 56%; } /* 宁夏枸杞 */
        .p-notoginseng{ top: 78%; left: 56%; } /* 云南三七 */
        .p-dendrobium { top: 68%; left: 81%; } /* 浙江铁皮石斛 */
        .p-saffron    { top: 58%; left: 24%; } /* 西藏藏红花 */
        .p-cistanche  { top: 28%; left: 45%; } /* 内蒙古肉苁蓉 */
        .p-angelica   { top: 52%; left: 51%; } /* 甘肃当归 */
        .p-ganoderma  { top: 56%; left: 74%; } /* 安徽灵芝 */
        .p-peony      { top: 48%; left: 73%; } /* 山东/安徽白芍 */

        .info-panel {
            background: var(--paper-color);
            border-radius: 12px;
            padding: 35px;
            box-shadow: inset 0 0 50px rgba(184, 134, 11, 0.1), 0 10px 30px rgba(0,0,0,0.1);
            border: 2px solid var(--gold);
            overflow-y: auto;
        }

        .herb-header { 
            display: flex; justify-content: space-between; align-items: flex-start;
            border-bottom: 2px solid var(--herb-green); padding-bottom: 20px; margin-bottom: 25px; 
        }
        .herb-header-text h2 { font-size: 32px; color: var(--herb-green); font-family: 'Ma Shan Zheng'; }
        .herb-header-text h3 { font-size: 16px; color: var(--accent-red); font-style: italic; }
        
        .herb-img-container {
            border: 4px solid #fff; box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border-radius: 8px; overflow: hidden; cursor: zoom-in; background: #fff;
        }
        .herb-img { width: 140px; height: 140px; object-fit: contain; display: block; transition: 0.5s; }
        .herb-img-container:hover .herb-img { transform: scale(1.1); }

        .content-section { margin-bottom: 25px; }
        .content-section h4 { 
            color: var(--herb-green); margin-bottom: 8px; 
            border-left: 5px solid var(--accent-red); padding-left: 12px; font-size: 1.1rem;
        }
        .content-section p { font-size: 16px; color: #444; text-align: justify; }
        .en-text { display: block; font-size: 14px; color: #777; font-style: italic; margin-top: 6px; }

        .placeholder { text-align: center; margin-top: 40%; opacity: 0.5; }

        #imgModal {
            display: none; position: fixed; z-index: 2000; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(0,0,0,0.9); justify-content: center; align-items: center; cursor: zoom-out;
        }
        #imgModal img { max-width: 90%; max-height: 90%; border: 5px solid var(--paper-color); border-radius: 5px; }

        .info-panel::-webkit-scrollbar { width: 6px; }
        .info-panel::-webkit-scrollbar-thumb { background: var(--gold); border-radius: 10px; }

        @media (max-width: 1024px) {
            .main-explorer { grid-template-columns: 1fr; height: auto; }
            .map-container { height: 500px; }
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <div class="logo-text">中华本草名贵药材图鉴 <span>Herbal Atlas of China</span></div>
            <div style="font-size: 14px; color: var(--paper-color); font-style: italic;">神农尝百草，本草载千秋</div>
        </nav>
    </header>

    <main class="main-explorer">
        <div class="map-container">
            <div class="pin p-ginseng" onclick="showHerb('ginseng', this)"></div>
            <div class="pin p-cordyceps" onclick="showHerb('cordyceps', this)"></div>
            <div class="pin p-goji" onclick="showHerb('goji', this)"></div>
            <div class="pin p-notoginseng" onclick="showHerb('notoginseng', this)"></div>
            <div class="pin p-dendrobium" onclick="showHerb('dendrobium', this)"></div>
            <div class="pin p-saffron" onclick="showHerb('saffron', this)"></div>
            <div class="pin p-cistanche" onclick="showHerb('cistanche', this)"></div>
            <div class="pin p-angelica" onclick="showHerb('angelica', this)"></div>
            <div class="pin p-ganoderma" onclick="showHerb('ganoderma', this)"></div>
            <div class="pin p-peony" onclick="showHerb('peony', this)"></div>
        </div>

        <div class="info-panel" id="infoPanel">
            <div class="placeholder" id="placeholder">
                <i class="fas fa-seedling fa-4x" style="color:var(--herb-green); margin-bottom:20px"></i>
                <p>点击地图上的朱砂光点解锁本草档案<br><i>Click points to explore herbal archives</i></p>
            </div>
            <div id="herbDetail" style="display:none">
                <div class="herb-header">
                    <div class="herb-header-text">
                        <h2 id="hName"></h2>
                        <h3 id="hEnName"></h3>
                    </div>
                    <div class="herb-img-container" onclick="zoomImage()">
                        <!-- referrerpolicy="no-referrer" 用于解决防盗链图片加载问题 -->
                        <img id="hImg" src="" alt="Herb" class="herb-img" referrerpolicy="no-referrer">
                    </div>
                </div>
                <div class="herb-content">
                    <div class="content-section">
                        <h4>产地 Origin</h4>
                        <p id="hOrigin"></p>
                        <span class="en-text" id="hOriginEn"></span>
                    </div>
                    <div class="content-section">
                        <h4>形态特征 Appearance</h4>
                        <p id="hDesc"></p>
                        <span class="en-text" id="hDescEn"></span>
                    </div>
                    <div class="content-section">
                        <h4>药用功效 Efficacy</h4>
                        <p id="hValue"></p>
                        <span class="en-text" id="hValueEn"></span>
                    </div>
                </div>
            </div>
        </div>
    </main>

    <div id="imgModal" onclick="this.style.display='none'">
        <img id="modalImg" src="" referrerpolicy="no-referrer">
    </div>

    <script>
        const herbData = {
            ginseng: {
                name: "人参 (Ginseng)", en: "Panax Ginseng - King of Herbs",
                img: "https://hockhuatonic.com/storage/2020/03/ginseng.png",
                origin: "吉林长白山、辽宁（道地药材）", originEn: "Changbai Mountains, Jilin/Liaoning Province",
                desc: "多年生草本。根部肥大，形若人形。以根入药，野生者称“野山参”，极其名贵。",
                descEn: "A perennial herb with a fleshy root resembling a human figure. Highly prized in traditional medicine.",
                value: "大补元气，复脉固脱，补脾益肺。被誉为“百草之王”。",
                valueEn: "Greatly replenishes vital energy (Qi), improves circulation, and strengthens the lungs."
            },
            cordyceps: {
                name: "冬虫夏草 (Cordyceps)", en: "Cordyceps Sinensis",
                img: "https://img.shoplineapp.com/media/image_clips/69bba4863f182861611a4723/original.png?1773905029=",
                origin: "西藏、青海（高海拔草甸）", originEn: "Tibet and Qinghai Plateaus",
                desc: "麦角菌科真菌寄生在蝙蝠蛾科幼虫上的复合体。冬为虫，夏为草。",
                descEn: "A unique complex of a fungus parasitizing caterpillar larvae. It is an insect in winter and a herb in summer.",
                value: "补肾益肺，止血化痰。对虚劳咳喘、腰膝酸痛有显著疗效。",
                valueEn: "Tonifies the kidneys and lungs, stops bleeding, and dissolves phlegm."
            },
            goji: {
                name: "宁夏枸杞 (Goji)", en: "Wolfberry / Lycium Barbarum",
                img: "https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Lycium_barbarum_-_Wolfberries_China_7-05.jpg/500px-Lycium_barbarum_-_Wolfberries_China_7-05.jpg",
                origin: "宁夏中宁（地理标志产区）", originEn: "Zhongning, Ningxia Province",
                desc: "茄科灌木。果实鲜红色，长椭圆形。富含胡萝卜素及抗氧化成分。",
                descEn: "A shrub with bright red, oblong berries. Renowned globally as a superfood.",
                value: "滋补肝肾，益精明目。用于视力减退、虚劳精亏。",
                valueEn: "Nourishes the liver and kidneys, and enhances vision."
            },
            notoginseng: {
                name: "三七 (San Qi)", en: "Panax Notoginseng",
                img: "https://bowuguan.bucm.edu.cn/images/content/2016-05/20160527115203328281.jpg",
                origin: "云南文山、广西", originEn: "Wenshan, Yunnan Province",
                desc: "多年生草本。根呈圆锥形。因生长期长，价值昂贵，古称“金不换”。",
                descEn: "A perennial herb with cone-shaped roots. Highly valued for its blood-healing properties.",
                value: "散瘀止血，消肿定痛。是云南白药的主要成分。",
                valueEn: "Dispels blood stasis, stops bleeding, and reduces swelling and pain."
            },
            dendrobium: {
                name: "铁皮石斛 (Dendrobium)", en: "Dendrobium Officinale",
                img: "https://5b0988e595225.cdn.sohucs.com/images/20180613/30a3147011e04aafb98c2648ee902f91.jpeg",
                origin: "浙江、安徽、云南（岩石峭壁）", originEn: "Zhejiang, Anhui, and Yunnan Provinces",
                desc: "兰科植物。茎圆柱形。生长在阴湿的岩石缝隙，被誉为“救命仙草”。",
                descEn: "An orchid that grows on damp cliffs. Known as a 'life-saving immortal herb'.",
                value: "益胃生津，滋阴清热。用于口干烦渴、胃阴不足。",
                valueEn: "Benefits the stomach and promotes fluid production; clears heat and nourishes Yin."
            },
            saffron: {
                name: "西藏红花 (Saffron)", en: "Crocus Sativus / Saffron",
                img: "https://copyright.bdstatic.com/vcg/creative/9c136d016086daba8fd576131910e609.jpg",
                origin: "西藏、上海（引种）", originEn: "Tibet, Shanghai (Cultivated)",
                desc: "鸢尾科球根花卉。药用部位为干燥的花柱及柱头。产量极低。",
                descEn: "A bulbous flower where only the dried stigmas are used. Extremely labor-intensive.",
                value: "活血化瘀，凉血解毒，解郁安神。调理气血之圣药。",
                valueEn: "Promotes blood circulation, clears toxins, and relieves depression."
            },
            cistanche: {
                name: "肉苁蓉 (Cistanche)", en: "Desert Cistanche",
                img: "https://www.chemicalbook.com//SupplyImg1/2024-07-18/202407190807425211047283677.png",
                origin: "内蒙古、新疆（干旱沙漠）", originEn: "Inner Mongolia and Xinjiang Deserts",
                desc: "寄生植物。寄生在梭梭树根部，被誉为“沙漠人参”。",
                descEn: "A parasitic herb growing on the roots of desert trees. Known as 'Desert Ginseng'.",
                value: "补肾阳，益精血，润肠通便。对体虚便秘有良效。",
                valueEn: "Tonifies kidney Yang, benefits essence and blood, and moistens intestines."
            },
            angelica: {
                name: "当归 (Dang Gui)", en: "Angelica Sinensis",
                img: "https://zyj.beijing.gov.cn/sy/whkp/202108/W020210816762836489736.jpg",
                origin: "甘肃岷县（道地药材产区）", originEn: "Minxian, Gansu Province",
                desc: "伞形科多年生草本。根部有特异浓郁香气。中医称为“妇科圣药”。",
                descEn: "A perennial herb with highly aromatic roots, fundamental in traditional therapy.",
                value: "补血活血，调经止痛，润肠通便。调理血虚血瘀。",
                valueEn: "Nourishes and activates blood, regulates menstruation, and relieves pain."
            },
            ganoderma: {
                name: "灵芝 (Lingzhi)", en: "Ganoderma Lucidum / Reishi",
                img: "https://upload.wikimedia.org/wikipedia/commons/8/81/Ganoderma_lucidum_01.jpg",
                origin: "安徽大别山、山东、福建", originEn: "Anhui, Shandong, and Fujian Mountains",
                desc: "多孔菌科真菌。菌盖呈木质，具漆样光泽。象征长寿吉祥。",
                descEn: "A woody mushroom with a glossy cap. A traditional symbol of longevity.",
                value: "补气安神，止咳平喘。用于心神不宁、失眠惊悸、虚劳短气。",
                valueEn: "Nourishes Qi, calms the mind, and relieves coughs and asthma."
            },
            peony: {
                name: "白芍 (Bai Shao)", en: "White Peony Root",
                img: "https://static.wixstatic.com/media/fd67df_8ccb76b7dad440ad81427a689d5804f7~mv2.webp",
                origin: "安徽亳州、浙江、四川", originEn: "Bozhou, Anhui Province",
                desc: "芍药科多年生草本。药用其根部，质地坚实，切面平坦。",
                descEn: "A perennial herb where the firm, processed roots are used medicinally.",
                value: "养血调经，敛阴止汗，柔肝止痛。用于月经不调、自汗盗汗。",
                valueEn: "Nourishes blood, regulates menstruation, and softens the liver."
            }
        };

        let currentActivePin = null;

        function showHerb(id, el) {
            if (currentActivePin) currentActivePin.classList.remove('active');
            el.classList.add('active');
            currentActivePin = el;

            const data = herbData[id];
            document.getElementById('placeholder').style.display = 'none';
            document.getElementById('herbDetail').style.display = 'block';
            
            document.getElementById('hName').innerText = data.name;
            document.getElementById('hEnName').innerText = data.en;
            document.getElementById('hImg').src = data.img;
            document.getElementById('hOrigin').innerText = data.origin;
            document.getElementById('hOriginEn').innerText = data.originEn;
            document.getElementById('hDesc').innerText = data.desc;
            document.getElementById('hDescEn').innerText = data.descEn;
            document.getElementById('hValue').innerText = data.value;
            document.getElementById('hValueEn').innerText = data.valueEn;

            const detail = document.getElementById('herbDetail');
            detail.style.opacity = 0;
            setTimeout(() => {
                detail.style.transition = '0.5s ease';
                detail.style.opacity = 1;
            }, 10);
        }

        function zoomImage() {
            const imgSrc = document.getElementById('hImg').src;
            const modal = document.getElementById('imgModal');
            const modalImg = document.getElementById('modalImg');
            modalImg.src = imgSrc;
            modal.style.display = 'flex';
        }
    </script>
</body>
</html>
