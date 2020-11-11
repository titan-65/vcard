<script>
    export let label;
</script>
<div>
    <nav
            class="navbar navbar-inverse bg-dark fixed-top navbar-expand-lg"
            id="sectionsNav">
        <div class="container">
            <div class="navbar-translate">
                    <a class="navbar-brand"> {label} </a>
                <button
                        class="navbar-toggler"
                        type="button"
                        data-toggle="collapse"
                        aria-expanded="false"
                        aria-label="Toggle navigation">
                    <span class="sr-only">Toggle navigation</span>
                    <span class="navbar-toggler-icon" />
                    <span class="navbar-toggler-icon" />
                    <span class="navbar-toggler-icon" />
                </button>
            </div>
            <div class="collapse navbar-collapse">
                <ul class="navbar-nav ml-auto">

                    <li class="dropdown nav-item">
                        <!-- svelte-ignore a11y-missing-attribute -->
                        <a class="nav-link">
                                <i class="material-icons">view_carousel</i>
                                Player Card

                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</div>
