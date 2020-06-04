# One-Page-Nav-for-Elementor
one page nav for Elementor pro smoth scroll navigation menu

# include customize for custom css
/*header main menu style*/
.header-section ul li:last-child a {
    border: 1px solid #fff;
    margin: 21px;
    padding: 10px 15px !important;
    border-radius: 3px;
}
 .header-section ul li:last-child a:after {
    bottom: -56%;
}
.header-section ul li:last-child:hover a:after {
    bottom: -56%;
}
@media(max-width:768px){
	.header-section nav{
		top:15px !important; 
	}
	.header-section ul li:last-child a{
		margin:0;
		border:0;
	}
}
