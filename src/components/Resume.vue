<template>

    <div class="keepit">
        <h2 class="heading"> My <span> resume </span> </h2>
        <div class="row">
            <div class="col-md-12">
                <div class="main-timeline">
                    <div class="timeline">
                        <a href="#" class="timeline-content">
                            <div class="timeline-icon"><i class="fa fa-globe"></i></div>
                            <h3 class="title">Web Designing</h3>
                            <p class="description">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                neque commodo
                            </p>
                        </a>
                    </div>
                    <div class="timeline">
                        <a href="#" class="timeline-content">
                            <div class="timeline-icon"><i class="fa fa-globe"></i></div>
                            <h3 class="title">Web Designing</h3>
                            <p class="description">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                neque commodo
                            </p>
                        </a>
                    </div>
                    <div class="timeline">
                        <a href="#" class="timeline-content">
                            <div class="timeline-icon"><i class="fa fa-globe"></i></div>
                            <h3 class="title">Web Designing</h3>
                            <p class="description">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                neque commodo
                            </p>
                        </a>
                    </div>
                    <div class="timeline">
                        <a href="#" class="timeline-content">
                            <div class="timeline-icon"><i class="fa fa-globe"></i></div>
                            <h3 class="title">Web Designing</h3>
                            <p class="description">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer males uada tellus
                                lorem, et condimentum neque commodo Integer males uada tellus lorem, et condimentum
                                neque commodo
                            </p>
                        </a>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {

    }
</script>

<style scoped>
    .keepit {
        margin-top: 100px;
        margin-bottom: 100px;
        padding-top: 11vh;
    }

    .main-timeline {
        font-family: 'Poppins', sans-serif;
        position: relative;
    }

    .main-timeline:after {
        content: '';
        display: block;
        clear: both;
    }

    .main-timeline .timeline {
        width: calc(50% + 120px);
        margin: 0 0 25px;
        float: right;
        position: relative;
    }

    .main-timeline .timeline-content {
        color: #fff;
        background: linear-gradient(#424956 50%, #343A3F 50%);
        min-height: 125px;
        padding: 20px 30px 20px 205px;
        display: block;
        position: relative;
        clip-path: polygon(0 0, 100% 0, 95% 50%, 100% 100%, 0 100%, 5% 50%);
    }

    .main-timeline .timeline-content:hover {
        text-decoration: none;
    }

    .main-timeline .timeline-icon {
        color: rgb(14, 13, 13);
        background-color: rgb(14, 13, 13);
        font-size: 35px;
        text-align: center;
        line-height: 115px;
        height: 115px;
        width: 115px;
        transform: translateY(-50%);
        position: absolute;
        left: 61px;
        top: 50%;
        clip-path: polygon(50% 0, 100% 20%, 100% 80%, 50% 100%, 0 80%, 0 20%);
    }

    .main-timeline .timeline-icon:before {
        content: '';
        background-color: #22C4E5;
        position: absolute;
        left: 13px;
        right: 13px;
        top: 13px;
        bottom: 13px;
        z-index: -1;
        clip-path: inherit;
    }

    .main-timeline .title {
        color: #22C4E5;
        font-size: 22px;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        margin: 0 0 5px;
    }

    .main-timeline .description {
        font-size: 13px;
        letter-spacing: 1px;
        line-height: 20px;
        margin: 0;
    }

    .main-timeline .timeline:nth-child(even) {
        float: left;
    }

    .main-timeline .timeline:nth-child(even) .timeline-content {
        padding: 20px 205px 20px 50px;
    }

    .main-timeline .timeline:nth-child(even) .timeline-icon {
        transform: translateY(-50%);
        left: auto;
        right: 60px;
    }

    .main-timeline .timeline:nth-child(4n+2) .timeline-icon:before {
        background-color: #22C4E5;
    }

    .main-timeline .timeline:nth-child(4n+2) .title {
        color: #22C4E5;
    }

    .main-timeline .timeline:nth-child(4n+3) .timeline-icon:before {
        background-color: #22C4E5;
    }

    .main-timeline .timeline:nth-child(4n+3) .title {
        color: #22C4E5;
    }

    .main-timeline .timeline:nth-child(4n+4) .timeline-icon:before {
        background-color: #22C4E5;
    }

    .main-timeline .timeline:nth-child(4n+4) .title {
        color: #22C4E5;
    }

    @media screen and (max-width:767px) {
        .main-timeline .timeline {
            width: 100%;
        }

        .main-timeline .timeline-content {
            padding-right: 50px;
        }

        .main-timeline .timeline:nth-child(even) .timeline-content {
            padding-left: 60px;
        }
    }

    @media screen and (max-width:576px) {
        .main-timeline .timeline {
            margin: 0 0 40px;
        }

        .main-timeline .timeline-content,
        .main-timeline .timeline:nth-child(even) .timeline-content {
            text-align: center;
            padding: 155px 40px 20px;
        }

        .main-timeline .timeline-icon,
        .main-timeline .timeline:nth-child(even) .timeline-icon {
            transform: translateY(0) translateX(-50%);
            left: 50%;
            right: auto;
            top: 21px;
        }
    }
</style>