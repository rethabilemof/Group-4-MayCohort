<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Group 4 PLP MayCohort</title>

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <link rel="stylesheet" href="css/style.css">
</head>

<body>

    <header id="top">
        <nav class="navbar navbar-expand-lg navbar-light">
            <div class="container">
                <a class="navbar-brand" href="#">&lt; Group 4 MayCohort &gt;</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                    aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#about-us">About Us</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#our-projects">Projects</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact Us</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <main class="container">
        <div id="bg-img1">
            <section class="introduction">
                <div class="vh-50 d-flex flex-column justify-content-center align-items-center text-center">
                    <p class="fs-4 mt-3">Hi there! We are the Group 4 team of PLP's MayCohort</p>
                    <p class="fs-4 fw-bold mb-1">A group of Aspiring Web Developers</p>
                    <p class="mb-4">We collaborate and learn together to build both frontend and backend projects</p>
                    <a href="#contact">
                        <button type="button" class="btn btn-dark">CONNECT WITH US</button>
                    </a>
                </div>
            </section>
        </div>

        <section class="about" id="about-us">
            <div class="row">
                <div class="col-md-6 text-center my-3">
                    <img class="w-75" src="./media/nerd-img2.jpg" alt="">
                </div>
                <div class="col-md-6">
                    <p class="fs-2 fw-bold">About Us</p>
                    <p>
                        We are a group of goofy nerds who like to learn about new programming languages and still have some fun too.
                        We have worked on assignments and project tasks related to:
                    </p>
                    <ul>
                        <li>Python and Django</li>
                        <li>HTML, CSS, Node JS, and MySQL</li>
                    </ul>
                    <p>We all have our own strengths and we work together to get things working.</p>
                </div>
            </div>
        </section>

        <section class="project" id="our-projects">
            <div class="row">
                <div class="col-md-6">
                    <p class="fs-2 fw-bold">Projects</p>
                    <p>The Expense Tracker is our most recent project</p>
                    <p>
                        Project Description: This is a simple expense tracker application built with Node.js, Express, and MySQL.<br>
                        Users can register, log in, add expenses and view all their expenses.
                        The project includes authentication to ensure users can only view and modify their own expenses.
                    </p>
                    <a href="https://github.com/barbzyqueen/week-4-backend-development-barbzyqueen.git" target="_blank">
                        <button type="button" class="btn btn-dark">VIEW SOURCE CODE</button>
                    </a>
                </div>
                <div class="col-md-6 text-center my-3">
                    <img class="w-75" src="media/expense_tracker.png" alt="">
                </div>
            </div>
        </section>

        <section class="contact" id="contact">
            <div id="bg-img2">
                <div class="d-flex flex-column align-items-center justify-content-center text-center">
                    <p class="fs-2 fw-bold">Let's Connect!</p>
                    <p class="mw-650">Reach out to any of our Group 4 Team Members listed below:</p>
                    <section class="contact-info">
                        <div class="row">
                            <!-- Insert each team member's info here -->
                            <!-- Replace '#' with actual LinkedIn and GitHub URLs where available -->

                            <!-- Rethabile Mofokeng -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px-2">Rethabile Mofokeng</li>
                                    <li class="px-2">
                                        <a href="https://github.com/rethabilemof" target="_blank">
                                            <i class="bi bi-github"></i>
                                        </a>
                                    </li>
                                    <li class="px-2">
                                        <a href="https://www.linkedin.com/in/rethabile-mofokeng-5230991b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
                                            <i class="bi bi-linkedin"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                            <!-- Amos Wanyama -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px-2">Amos Wanyama</li>
                                    <li class="px-2">
                                        <a href="https://github.com/amoswanyama" target="_blank">
                                            <i class="bi bi-github"></i>
                                        </a>
                                    </li>
                                    <li class="px-2">
                                        <a href="https://www.linkedin.com/in/amos-wanyama-ab679699/" target="_blank">
                                            <i class="bi bi-linkedin"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                            <!-- Raphael Makokha Alietsi -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px-2">Raphael Makokha Alietsi</li>
                                    <li class="px-2">
                                        <a href="https://github.com/Raphael-alietsi" target="_blank">
                                            <i class="bi bi-github"></i>
                                        </a>
                                    </li>
                                    <li class="px-2">
                                        <a href="https://www.linkedin.com/in/raphael-makokha-alietsi-008a6374?trk=contact-info" target="_blank">
                                            <i class="bi bi-linkedin"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                            <!-- Akinnuoye Samuel -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px-2">Akinnuoye Samuel</li>
                                    <li class="px-2">
                                        <a href="https://github.com/samuelldmj" target="_blank">
                                            <i class="bi bi-github"></i>
                                        </a>
                                    </li>
                                    <li class="px-2">
                                        <a href="https://www.linkedin.com/in/akinnuoye-samuel97/" target="_blank">
                                            <i class="bi bi-linkedin"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                            <!-- Barbara Mangiri -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px-2">Barbara Mangiri</li>
                                    <li class="px-2">
                                        <a href="https://github.com/barbzyqueen" target="_blank">
                                            <i class="bi bi-github"></i>
                                        </a>
                                    </li>
                                    <li class="px-2">
                                        <a href="https://www.linkedin.com/in/barbara-mangiri-97480b14b" target="_blank">
                                            <i class="bi bi-linkedin"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>

                            <!-- Iddy hamis -->
                            <div class="col-md-6 contact-list">
                                <ul class="d-flex flex-row list-unstyled">
                                    <li class="px

<!-- Iddy hamis -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Iddy hamis</li>
        <li class="px-2">
            <a href="https://github.com/Iddyh" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/iddy-maulid-744a332b0" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Camilla Patricia -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Camilla Patricia</li>
        <li class="px-2">
            <a href="https://github.com/its-Cammy" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/patricia-camilla-6a32b5238?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B29gM3s5sRh6PkPnYz7TQsA%3D%3D" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Maryann Omenuko -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Maryann Omenuko</li>
        <li class="px-2">
            <a href="https://github.com/obieomens" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/maryann-omenuko-12079b286" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Akui Kiken -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Akui Kiken</li>
        <li class="px-2">
            <a href="https://github.com/Kiken24" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/akui-k-aa6586106" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Blessing Agbo -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Blessing Agbo</li>
        <li class="px-2">
            <a href="https://github.com/Bliss-web" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/blessing-agbo-40865a174" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Peter Mwiti Muchai -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Peter Mwiti Muchai</li>
        <li class="px-2">
            <a href="https://github.com/MwitiPeter" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/peter-mwiti-muchai" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Doctor Sakhile Mahlalela -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Doctor Sakhile Mahlalela</li>
        <li class="px-2">
            <a href="https://github.com/dsmahlalelah" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/doctorh-sakhile-48a06b2ba" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Martin Gitau -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Martin Gitau</li>
        <li class="px-2">
            <a href="https://github.com/Nitram099" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <!-- LinkedIn link not provided -->
            <!-- Replace '#' with the actual LinkedIn URL -->
            <a href="#" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Dennis karani -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Dennis karani</li>
        <li class="px-2">
            <a href="https://github.com/Denniskalph003" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/dennis-karani-analyst-healthtech" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- James Juma -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">James Juma</li>
        <li class="px-2">
            <a href="https://github.com/JumaGathairu" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/james-juma-333753270" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Oluwadamilola Oke -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Oluwadamilola Oke</li>
        <li class="px-2">
            <a href="https://github.com/DamilolaOke" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/oluwadamilola-oke-600a271b3" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Victoria Rich -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Victoria Rich</li>
        <li class="px-2">
            <a href="https://github.com/Rich-victoria" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/victoria-rich-958a40ab" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Tsholofelo Moeketsane -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Tsholofelo Moeketsane</li>
        <li class="px-2">
            <a href="https://github.com/TsholofeloMoeketsane" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/tsholofelo-moeketsane-8b961b121" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Ahmed Sulaimom -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Ahmed Sulaimom</li>
        <li class="px-2">
            <a href="https://github.com/AS-GLOBALTECH" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/sulaimom-ahmed-5231b9309" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Vincent Mburu -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Vincent Mburu</li>
        <li class="px-2">
            <a href="https://github.com/vinceMburu123" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/vinny-jude" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Minenhle Thusi -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Minenhle Thusi</li>
        <li class="px-2">
            <a href="https://github.com/minniemathe15" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/minenhle-thusi-4aa443269" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Geoffrey Nzule -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Geoffrey Nzule</li>
        <li class="px-2">
            <a href="https://github.com/Geoffrey-Nzule" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/jeff-nzule-569146205?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Faith Oluoch -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Faith Oluoch</li>
        <li class="px-2">
            <a href="https://github.com/Wonder24f" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/faith-wonder-5b8031201" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Samuel Mutuvi -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Samuel Mutuvi</li>
        <li class="px-2">
            <a href="https://github.com/Samuelmutuvi" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/samuel-mutuvi-8509bb28a" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Cynthia Wahome -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Cynthia Wahome</li>
        <li class="px-2">
            <a href="https://github.com/CynthiaWahome" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <!-- LinkedIn link not provided -->
            <!-- Replace '#' with the actual LinkedIn URL -->
            <a href="#" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>

<!-- Eugene Wesonga -->
<div class="col-md-6 contact-list">
    <ul class="d-flex flex-row list-unstyled">
        <li class="px-2">Eugene Wesonga</li>
        <li class="px-2">
            <a href="https://github.com/Wesonga01" target="_blank">
                <i class="bi bi-github"></i>
            </a>
        </li>
        <li class="px-2">
            <a href="https://www.linkedin.com/in/eugene-wesonga-930769314" target="_blank">
                <i class="bi bi-linkedin"></i>
            </a>
        </li>
    </ul>
</div>
