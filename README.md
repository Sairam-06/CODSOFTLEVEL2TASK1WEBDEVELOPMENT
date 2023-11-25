# CODSOFTLEVEL2TASK1WEBDEVELOPMENT
----------->>>>>HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />

    <meta http-equiv="X-UA-Compatible" content="IE=edge" />

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>The Tribute Website | A.P. J Abdul Kalam</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>
    <div class="container">
        <div class="content">
            <section class="top_section">
                <div class="image_container">
                    <img src="abdul sir.jpg" alt="tribute" />
                </div>
                <div>
                    <h1>A . P . J Abdul Kalam Sir </h1>
                    <h4>1931 - 2015</h4>
                </div>
            </section>
            <section class="about_section">
                <h2>Missile Man of India</h2>
                <p>
                    <b>Avul Pakir Jainulabdeen Abdul Kalam</b> 15 October 1931 – 27 July
                    2015) was an Indian aerospace scientist who served as the 11th
                    president of India from 2002 to 2007. He was born and raised in
                    Rameswaram, Tamil Nadu and studied physics and aerospace
                    engineering. He spent the next four decades as a scientist and
                    science administrator, mainly at the Defence Research and
                    Development Organisation (DRDO) and Indian Space Research
                    Organisation (ISRO) and was intimately involved in India's civilian
                    space programme and military missile development efforts.<a
                        href="https://www.drdo.gov.in/sites/default/files/drdo-news-documents/din-28july2019.pdf">[1]</a>
                    He thus
                    came to be known as the Missile Man of India for his work on the
                    development of ballistic missile and launch vehicle
                    technology.<a href="https://www.dqindia.com/contribution-apj-abdul-kalam-isro-drdo/">[2]</a> He also
                    played a pivotal organisational,
                    technical, and political role in India's Pokhran-II nuclear tests in
                    1998, the first since the original nuclear test by India in 1974.
                </p>
            </section>
            <section class="biography_section">
                <br>
                <br>
                <h3>About The Legend</h3>
                <ul>
                    <li>
                        A.P.J. Abdul Kalam served as the 11th President of India from 2002 to 2007.
                    </li>
                    <li>
                        Kalam earned a degree in aeronautical engineering from the Madras Institute of Technology and in
                        1958 joined the Defence Research and Development Organisation (DRDO).
                    </li>
                    <li>
                        In 1969, he moved to the Indian Space Research Organisation, where he was project director of
                        the SLV-III, the first satellite launch vehicle that was both designed and produced in India.
                    </li>
                    <li>
                        Rejoining DRDO in 1982, Kalam planned the program that produced a number of successful missiles,
                        which helped earn him the nickname <strong> “Missile Man.”</strong>
                    </li>
                    <li>
                        Among those successes was Agni, India's first intermediate-range ballistic missile, which
                        incorporated aspects of the SLV-III and was launched in 1989.
                    </li>
                    <li>
                        Kalam received <b>7</b> honorary doctorates from <b>40</b> universities. The Government of India
                        honoured him with the <b>Padma Bhushan in 1981</b> and the <b>Padma Vibhushan in 1990</b> for
                        his work with ISRO and DRDO and his role as a scientific advisor to the Government.
                    </li>
                    <li> In 1997, Kalam received India's highest civilian honour, the Bharat Ratna, for his contribution
                        to the scientific research and modernisation of defence technology in India. In 2013, he was the
                        recipient of the Von Braun Award from the National Space Society "to recognize excellence in the
                        management and leadership of a space-related project".
                    </li>
                    <li>
                        A prominent road in New Delhi was renamed from Aurangzeb Road to <b>Dr APJ Abdul Kalam Road</b>
                        in August 2015.
                    </li>
                    <li>
                        In February 2018, scientists from the Botanical Survey of India named a newly found plant
                        species as Drypetes kalamii, in his honour.
                    </li>


        </div>
        </section>
        <footer>
            <p>
                Read more about A. P. J. Abdul Kalam on
                <a href="https://en.wikipedia.org/wiki/A._P._J._Abdul_Kalam">Wikipedia.</a>
                <br>
                Tribute Page by Rajnish Kumar
            </p>
        </footer>
    </div>
    </div>
</body>

</html>
------------->>>>CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  .container {
    background-image: linear-gradient(120deg, orange, white, green);
    /* opacity: 0.9; */
    min-height: 100vh;
    border: 5px solid #1d1e4c;
  }
  
  .content {
    max-width: 1100px;
    margin: 0 auto;
  }
  .top_section {
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
  }
  .top_section h1 {
    font-size: 50px;
    font-weight: bold;
    color: #1d1e4c;
    text-transform: uppercase;
  }
  .top_section h4 {
    font-size: 30px;
    text-align: end;
  }
  
  .image_container {
    border-radius: 50%;
    overflow: hidden;
  }
  
  .image_container,
  img {
    width: 460px;
    height: 400px;
  }
  .about_section {
    margin-top: 50px;
  }
  .about_section h2 {
    font-size: 70px;
    font-weight: 400;
    margin-bottom: 20px;
  }
  .about_section p {
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 1.2px;
    text-align: justify;
  }
  .biography_section {
    margin: 50p;
    font-size: large;
    font-family: 'Times New Roman', Times, serif;
  }
  .biography_section h3 {
    margin-bottom: 20px;
  }
  .biography_section ul {
    margin-left: 50px;
  }
  .biography_section li {
    margin-bottom: 15px;
  }
  a{
    color: rgb(3, 32, 255);
  }
  
  footer {
    margin: 50px 0;
    margin-right: 20px;
  }
  footer p {
    text-align: center;
  }
