<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pankaj Parmar GIS Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <script src="https://kit.fontawesome.com/ce9c673d69.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/Logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header"><b>Home</b></a></li>
                    <li><a href="#about"><b>About</b></a></li>
                    <li><a href="#services"><b>Servives</b></a></li>
                    <li><a href="https://uploads.knightlab.com/storymapjs/9bf1a0480f911604e51ce9be3751ba53/portfolio/index.html"><b>Story Map</b></a></li>
                    <li><a href="#portfolio"><b>Portfolio</b></a></li>
                    <li><a href="#contact"><b>Contact</b></a></li>
                </ul>
                <i class="fa fa-minus" onclick="closemenu()"></i>
                <i class="fa fa-caret-square-down" onclick="openmenu()"></i>
            </nav>            
            <div class="header-text">
                <p>Geospatial Analyst</p>
                <h1>Hi, I'm <span>Pankaj</span> <br>Parmar from Sheffield</h1>
            </div>
        </div>
    </div>
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="images/My-photo.jpg">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About Me</h1>
                    <p>Orginally from Bhiwani, India. Currently living in Sheffield, UK. Current hobbies outside of GIS include playing volleyball, listening to music, and creating animated GIFs. Proficient in Hindi, English, Sanskrit, and currently learning Chinese.</p>
                    <div class="tab-titles">
                        <p class="tab-links active-link" onclick="opentab('skills')">Skills</p>
                        <p class="tab-links" onclick="opentab('experience')">Experience</p>
                        <p class="tab-links" onclick="opentab('education')">Education</p>
                    </div>
                    <div class="tab-contents active-tabs" id="skills">
                        <ul>
                            <li><span>Geospatial Analyst</span><br>GIS Developer/Consultant</li>
                            <li><span>Geospatial Web tools</span><br>Online story maps creation and OSM data gathering</li>
                            <li><span>Remote Sensing and satellite imagery</span><br>Climate change and environment monitoring</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="experience">
                        <ul>
                            <li><span>Jan 2023 - Nov 2023</span><br>Geospatial Analyst at Automatic Knowledge</li>
                        </ul>
                    </div>
                    <div class="tab-contents" id="education">
                        <ul>
                            <li><span>2023</span><br>MSc in Applied GIS from The University of Sheffield, United Kingdom</li>
                            <li><span>2021</span><br>BA Hons (Geography) from The University Of Delhi, India</li>
                            <li><span>2018</span><br>Highschool from the Central Board Of Secondary Education, Delhi, India</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My Services</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-map"></i>
                    <h2>GIS Consultancy</h2>
                    <p>Worked as GIS Consultant for clients as part of academics and while working for Automatic Knowledge Ltd.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-earth-europe"></i>
                    <h2>Remote Sensing</h2>
                    <p>Experience of working with satellite imagery datasets for measuring the Flood disaster, preparedness plan, Landuse and Landcover analysis, Air quality monitoring and climate change.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-chart-area"></i>
                    <h2>Spatial and Statistical data analysis</h2>
                    <p>Proficient in using Python, R and web tools like Overpass QL, MapBox for spatial and statistical analysis.</p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <i class="fa-solid fa-chart-area"></i>
                    <h2>Cartography</h2>
                    <p>Styled cartographic maps and visualizations during postgraduation as well as while working with Dr Rae at Automatic Knowledge Ltd.</p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <div id="portfolio">
        <div class="container">
            <h1 class="sub-title"> My Work</h1>
            <div class="work-list">
                <div class="work">
                    <img src="images/Connectivity Path.png">
                    <br>
                    <p>Habitat Analysis of Wythenshawe’s woodlands for Lesser Spotted Woodpeckers</p>
                    <div class="layer">
                        <h3></h3>
                        <p></p>
                        <a href="https://docs.google.com/document/d/1vNIfxtI4fZ_YOghxlinMfPlScsdkobeg/edit?usp=sharing&ouid=105189899451833128882&rtpof=true&sd=true"><i class="fa-solid fa-file-lines"></i></a> 
                    </div>
                </div>
                <div class="work">
                    <img src="images/TravelTime.png">
                    <br>
                    <p>Travel time to Radiotherapy centres across the UK</p>
                    <div class="layer">
                        <h3>Travel
