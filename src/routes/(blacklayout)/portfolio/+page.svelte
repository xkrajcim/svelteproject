<div class="main">

    <svg class="lens" width="1799" height="1692" viewBox="0 0 1799 1692" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g opacity="0.2">
        <path d="M1086.01 1122.12L1559.96 1118.88C1656.73 847.752 1619.88 653.125 1484.49 434.28L1086.01 1122.12Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        <path d="M755.242 1146.15L996.48 1554.12C1279.48 1501.34 1429.15 1371.59 1550.17 1144.48L755.242 1146.15Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        <path d="M567.265 875.862L332.683 1287.7C518.887 1507.25 705.796 1572.84 963.024 1565.27L567.265 875.862Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        <path d="M713.931 578.533L239.971 578.685C141.443 849.181 177.02 1044.04 310.982 1263.76L713.931 578.533Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        <path d="M1043.03 545.699L801.793 137.725C518.79 190.502 369.125 320.26 248.105 547.368L1043.03 545.699Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        <path d="M1232.47 820.56L1465.16 407.655C1277.96 188.956 1090.75 124.221 833.558 132.968L1232.47 820.56Z" stroke="black" stroke-opacity="0.7" stroke-width="2"/>
        </g>
        </svg>
        
        
        
    <div class="portfolio">

        <div class="portfolio-item">
            <h3>
                automotive
            </h3>
            <div class="portfolio-item-image" id="automotive">
            </div>
        </div>

 
        <div class="portfolio-item">
            <h3>
                behind the scenes
            </h3>
            <div class="portfolio-item-image" id="behindscenes">
            </div>
        </div>


    </div>

</div>

<style>

    .main{
        width: 80vw;
        height :100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        margin-left: 20vw;
        position: relative;
        overflow: hidden;
    }

    .lens{
        position: absolute;
        right: -280px;
        z-index: 0;
    }

    .portfolio{
        display: flex;
        flex-direction: row;
        width: 100%;
        justify-content: space-around;
        z-index: 10;
    }

    .portfolio-item{
        height: 500px;
        width: 400px;
        cursor: pointer;
        overflow: hidden;
        position: relative;
    }

    .portfolio-item-image{
        height: 100%;
        width: 100%;
        background-size: cover;
        background-position: center;
        transition: transform 0.5s ease-out;
    }

    #automotive{
        background-image: url('./DSC01824-Edit.JPG');
    }   
    #behindscenes{
        background-image: url('./DSC05447.JPG');
    }

    h3{
        position: absolute;
        text-align: center;
        top: 30%;
        width: 100%;
        padding: 20px 0;
        background-color: white;
        font-size: 32px;
        font-weight: 300;
        letter-spacing: 0.35em;
        z-index: 20;
        transition: 0.5s ease-out;
    }

    .portfolio-item:hover .portfolio-item-image{
        transform: scale(1.2);
    }

    .portfolio-item:hover h3{
        top: 40%;
        background-color: rgba(0, 0, 0, 0);
        color: white;
        transform: scale(1.2);
    }

</style>
