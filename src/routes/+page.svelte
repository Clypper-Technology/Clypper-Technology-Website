
<script lang="ts">
    import { Button } from "$lib/components/ui/button";
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
        opacity: 0; /* Start elements as invisible */
        animation: fadeIn 1s ease forwards; /* Apply the animation */
    }


    .first-line {
        margin-bottom: 50px;
        color: #fff;
        font-size: 58px;
        width: 100%;
    }

    .second-line {
        margin-bottom: 50px;
        display: flex;
        justify-content: center;
        font-weight: 500;
        width: 100%;
        font-size: 58px;
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
    }

    .showcase {
        background-color: var(--whiteish);
        height: 100vh;
    }
    
    .bread-text {
        max-width: 800px;
        font-size: 18px;
    }

</style>

<div class="main">
    <section class="hero">
        <div class="cta-section">
            <div class="text-section">
                <div class="first-line">
                    <p class="">Scaleable</p>
                </div>
                <div class="second-line">
                    <p>High-Performance</p>
                </div>
                <div class="third-line">
                    <p class="">Software Solutions</p>
                </div>
            </div>
            <div>
                <p class="medium-font bold">Streamline, Optimize and automate your bussiness</p>
                <p class="bread-text margin-top-m"> From web and desktop applications to robust, high-performance e-commerce platforms,
                    we design and develop scalable solutions that are tailored to meet your specific business needs.
                    Our focus is on creating systems that not only simplify and automate complex processes but also
                    enhance your operational efficiency and drive measurable results. Our solutions are crafted with a
                    commitment to high performance, ensuring that your business can scale seamlessly as it grows.</p>
                <button class="light margin-top-m">See more</button>
            </div>
        </div>
    </section>

    <section class="showcase"></section>
</div>