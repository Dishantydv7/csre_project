--color-2-dark : original color

.x1 {
	display: flex;
	justify-content: space-between;
    align-items: center;
	margin-top: 1%;
}

.y1, .y2, .y3 {
	width: 33.33%;
	text-align: left;
}
.y3{
max-width: 16vw;
border: 2px solid black;
	border-radius: 2%;
	box-shadow: 10px 0px 10px rgba(0, 0, 0, 0.65);
}

.y1 {
	font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
	font-size: larger;
	font-weight: 400;
}



previous one :
.x1 {
	display: flex;
	flex-direction: row;
	justify-content: space-evenly;
	align-items: center;
	margin-top: 1%;
}

.y1 {
	font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
	font-size: larger;
	font-weight: 400;
}

.y3 {
	max-width: 12vw;
	border: 2px solid black;
	border-radius: 2%;
	box-shadow: 10px 0px 10px rgba(0, 0, 0, 0.65);
	/* This will add a shadow to the right */
}