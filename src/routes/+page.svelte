
<script lang="ts">
</script>

<style>
    .hero {
        justify-content: center;
        width: 100%;
        align-items: center;
    }

    .cta-section {
        padding: 40px 0px;
        width: 100%;
        max-width: 1080px;
        height: fit-content;
    }

    .text-section {
        padding: 40px 0px;
        margin-bottom: 40px;
    }

    .first-line {
        margin-bottom: 50px;
        color: #fff;
        font-size: 58px;
        width: 100%;
        animation-delay: 1s;
    }

    .second-line {
        margin-bottom: 50px;
        display: flex;
        justify-content: center;
        flex-direction: column;
        font-weight: 500;
        width: 100%;
        font-size: 58px;
        animation-delay: 1.5s;
        align-items: center;
    }

    .third-line {
        margin-bottom: 50px;
        display: flex;
        justify-content: flex-end;
        width: 100%;
        font-size: 58px;
        text-decoration: underline;
        text-decoration: 3px solid var(--whiteish);
        line-height: 1.5em;
        animation-delay: 2s;
    }

    .bread-text {
        max-width: 800px;
        font-size: 18px;
        animation-delay: 2.2s;
    }

    .spacer {
        height: 5px;
        width: 100px;
        border-radius: 20px;
        background-color: var(--whiteish);
    }

    .nested-third-line {
        display: flex;
        flex-direction: column;
        align-items: flex-end;
    }

    .bread-header {
        animation-delay: 2s;
    }

    .bread-button {
        animation-delay: 2.4s;
    }

    .title {
        font-size: 68px;
        font-weight: 700;
        margin-bottom: 80px;
    }

    .second-line .spacer {
        display: none;
    }

    @media (max-width: 472px) {
        .title {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .first-line, .second-line, .third-line {
            font-size: 30px;
            width: fit-content;
            align-items: flex-start;
        }

        .spacer {
            width: 100%;
        }

        .second-line .spacer {
            display: block;
        }

        .third-line {
            justify-content: flex-start;
        }

        .text-section {
            margin-bottom: 10px;
        }

        .cta-section {
            padding: unset;
        }
        .hidden-link {
            position: fixed;
            bottom: -300px;
        }
    }


</style>

<div class="main">
    <section class="hero">
        <div class="cta-section">
            <h1 class="title fade-in">Clypper Technology</h1>
            <div class="text-section">
                <div class="first-line fade-in">
                    <p class="">Scaleable</p>
                    <div class="spacer"/>
                </div>
                <div class="second-line fade-in">
                    <p>High-Performance</p>
                    <div class="spacer"/>
                </div>
                <div class="third-line fade-in">
                    <div class="nested-third-line ">
                        <p class="">Software Solutions</p>
                        <div class="spacer third-spacer"/>
                    </div>
                </div>
            </div>
        </div>
        <h2>We are currently building...</h2>
        <h3>You can reach us at: Contact@clyppertechnology.com</h3>
    </section>
    <a class="hidden-link" href="/tax-preference"></a>
    <!--
    <section class="light">
        <div class="max-width">
            <h3 class="bread-header medium-font bold fade-in-slow">Streamline, Optimize and automate your bussiness</h3>
            <p class="bread-text margin-top-m fade-in fade-in-slow"> From web and desktop applications to robust, high-performance e-commerce platforms,
                we design and develop scalable solutions that are tailored to meet your specific business needs.
                Our focus is on creating systems that not only simplify and automate complex processes but also
                enhance your operational efficiency and drive measurable results. Our solutions are crafted with a
                commitment to high performance, ensuring that your business can scale seamlessly as it grows.</p>
            <button class="light bread-button margin-top-m fade-in-slow">See more</button>
        </div>
    </section>-->
</div>