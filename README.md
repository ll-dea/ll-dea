<svg fill="none" viewBox="0 0 100% 100%" width="100%" height="100%" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
  <div xmlns="http://www.w3.org/1999/xhtml">
    <style>
      * {
        margin: 0;
        padding: 0;
        color: inherit;
        text-decoration: none;
        list-style: none;
        outline: none;
        box-sizing: border-box;
      }

			.body {
				background: linear-gradient(270deg, #8445c3, #d838ab, #d4145a, #fbb03b);
				background-size: 300% 300%;
				height: 100vh;
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
				font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        border-radius: 0.75rem;
				color: #FFFFFF;

				-webkit-animation: InfiniteScroll 15s ease infinite;
				-moz-animation: InfiniteScroll 15s ease infinite;
				animation: InfiniteScroll 15s ease infinite;
			}

			.container {
        height: calc(100% - 10px);
        width: calc(100% - 10px);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
				gap: 10px;
      }

			.container h2 {
				text-align: center;
				font-size: 3.5vw;
				line-height: 1.75rem;
			}

			@-webkit-keyframes InfiniteScroll {
				0%{background-position:0% 50%}
				50%{background-position:100% 50%}
				100%{background-position:0% 50%}
			}
			@-moz-keyframes InfiniteScroll {
				0%{background-position:0% 50%}
				50%{background-position:100% 50%}
				100%{background-position:0% 50%}
			}
			@keyframes InfiniteScroll {
				0%{background-position:0% 50%}
				50%{background-position:100% 50%}
				100%{background-position:0% 50%}
			}

			@media only screen and (max-width: 500px) {
				.container h2 {
					font-size: 5vw;
					line-height: 1.5rem;
				}
			}
      
    </style>
    <div class='body'>
      <div class='container'>
        <h2>👋🏻 Hey there, I'm Dea!</h2>
    		<h2>I'm a Computer and Software engineering student</h2>
      </div>
    </div>
  </div>
  </foreignObject>
</svg>
