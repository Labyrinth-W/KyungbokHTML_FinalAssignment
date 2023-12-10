<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Store</title>
    <style>
        *{
            margin:0px;
            padding:0px;
        }
        .page_frame{
            position:relative;
        }
        .page_mainmenu{
            margin-top:0px;
            margin-bottom:0px;
            overflow:hidden;
            background-color:black;
            z-index:30px;
        }
        .page_menu{
            position:relative;
            margin-top:0px;
            margin-left:0px;
            margin-bottom:0px;
            margin-right:0px;
            overflow:hidden;
            overflow-y:auto;
        }
        .mainmenu_contents{
            background:#171a21;
            font-size:24px;
            position:relative;
            min-height:100%;
        }
        .mainmenu_contents_items{
            font-weight:200px;
        }
        .menuitem{
            border-top:1px solid #171a21;
            border-bottom:1px solid #171a21;

            position: relative;
            color: #bdbdbd;
            background:#171a21;
            transition: background 0.25s, color 0.25s;

            display:block;
            padding:0px 12px;
            overflow:hidden;
            text-overflow:ellipsis;
            white-space:nowrap;
            line-height:2.5em;
            text-decoration:none;
            cursor:pointer;
        }
        .submenu_store{
            display:none;
        }
        .mainmenu_footer_spacer{
            height:200px;
        }
        .mainmenu_footer{
            margin-left:0px;
            margin-right:0px;
            margin-bottom:0px;
            font-size:30px;
            white-space:normal;
            color:#8a8a8a;
            padding:0px 12px 24px 12px;
        }
    </style>
</head>
<body>
    <div class="page_frame">
        <div class="page_mainmenu">
            <div class="page_menu" id="page_menu">
                <div class="mainmenu_contents">
                    <div class="mainmenu_contents_items">

                        <a class="menuitem" href="https://www.naver.com/">Login</a>

                        <div class="submenu_store" data-submenuid="store">
                            <a class="submenuitem" href="">Home</a>
                        </div>

                        <a class="menuitem supernav" href="" data-tooltip-type="selector" data-tooltip-content=".submenu_community">Community</a>
                    </div><!--mainmenu_contents_items-->
                    
                    <div class="mainmenu_footer_spacer  "></div>
                    <div class="mainmenu_footer">

                        <img alt="Cyberpunk 2077" src="https://cdn.akamai.steamstatic.com/steam/apps/1091500/header_alt_assets_5.jpg?t=1701872789">Cyberpunk 2077 : ₩30,000
                        <img alt="EA SPORTS FC™ 24" src="https://cdn.akamai.steamstatic.com/steam/apps/2195250/header.jpg?t=1701266064">EA SPORTS FC 24 : ₩40,000
                        <img alt="Diablo® IV" src="https://cdn.akamai.steamstatic.com/steam/apps/2344520/header.jpg?t=1701194709">Diablo® IV : ₩50,000
                        <img alt="Resident Evil 4" src="https://cdn.akamai.steamstatic.com/steam/apps/2050650/header_alt_assets_0.jpg?t=1701394560">Resident Evil 4 : ₩60,000

                        <div class="mainmenu_footer_logo">
                            <img src="https://store.akamai.steamstatic.com/public/shared/images/responsive/logo_valve_footer.png">
                        </div><!--mainmenu_footer_logo-->
                        This page is from the game store. Feel free to look around.
                    </div><!--mainmenu_footer-->
                </div><!--mainmenu_contents-->
            </div><!--responsive_page_menu-->
        </div><!--responsive_page_mainmenu-->
    </div><!--responsive_page_frame-->
</body>
</html>
