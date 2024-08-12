<script>
</script>

<style>
    .header {
        width: 100vw;
        height: 70px;
        display: flex;
        align-items: center;
        border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    }

    .header-content-wrapper {
        height: 70px;
        background-color: var(--black);
        width: 100%;
        padding: 0px 40px;
        position: fixed;
        top: 0;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        z-index: 9999;
    }

    .nav {
        display: flex;
        margin: 10px;
        list-style-type: none;
    }
    .nav-item {
        transition-duration: 0.3s;
        display: flex;
        margin-right: 40px;
    }
    a {
        color: var(--whiteish);
        transition-duration: 0.3s;
        text-decoration: none;
        font-weight: 500;
        font-size: 20px;
    }

    .nav-item:hover {
        background-color: var(--hover-black);
        border-radius: 8px;
    }

    .nav-item:hover a {
        color: var(--hover-white);
        border-bottom: unset;
    }

    @media (max-width: 472px) {
        .header-content-wrapper {
            padding: 0px 20px;
        }
    }

</style>

<div class="header">
    <div class="header-content-wrapper">
        <h2><a href="/">Clypper Technology</a></h2>
        <nav class="nav">
            <!--
            <li class="nav-item">
                <a href="/tax-preference/">Tax Preference</a>
            </li>
            <li class="nav-item">
                <a href="/about/">About</a>
            </li>-->
        </nav>
    </div>
</div>