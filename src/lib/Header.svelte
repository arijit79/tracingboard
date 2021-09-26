<header>
    <span>Board</span>
    <button>Add Feed</button>
</header>

<style lang="scss">
    header {
        width: 100%;
        box-shadow: 0 5px 5px rgb(200, 200, 200);
        height: 3.5rem;
        line-height: 3.25rem;
        margin: 0;
        display: flex;
        justify-content: space-between;

        --primary-color: rgb(0, 135, 215);
        --font-color: white;

        span {
            margin-left: 5rem;
            font-size: 2.25rem;
            font-weight: 1000;
        }

        button {
            margin-right: 10rem;
            height: 2.5rem;
            margin-top: 0.6%;
            background-color: var(--primary-color);
            color: var(--font-color);
            padding: 0 1rem 0 1rem;
            font-weight: bold;
            outline: none;
            border: 2px solid var(--primary-color);
            transition: background 0.1s;

            &:hover {
                background-color: var(--font-color);
                color: var(--primary-color);
            }
        }
    }
</style>
