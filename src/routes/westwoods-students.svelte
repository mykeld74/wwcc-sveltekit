<script>
	import Img from '$components/image.svelte';
</script>

<svelte:head>
	<title>Westwoods Students | Westwoods Community Church</title>
</svelte:head>

<div class="hero">
	<div class="studentsLogoContainer">
		<Img source="studentsLogo" altTag="Students Logo" />
	</div>
	<h1>Westwoods Students</h1>
</div>
<div class="container">
	<p>
		Westwoods Students is a gathering of 6th-12th grade students with the purpose of fostering space
		for students to be known, noticed and encouraged in the journey of life. You belong before you
		believe and we seek to offer the environment where students can be themselves by connecting
		amazing adult leaders to come alongside each student over these formative years. We have weekly
		gatherings during the school year on Monday Evenings at 6:30 pm for fun, connection, missional
		communities and to encourage the students in the way of Jesus in their lives with friends,
		family, at school, at home and ultimately who they are becoming.
	</p>

	<p>
		We would love to get to know your students and have them join this community of fellow students
		and leaders.
	</p>

	<p>
		This Summer we have several gatherings to connect, enjoy the summer days and intentionally
		encourage one another in the way of Jesus. We will seek to press into the truth that
		apprenticeship to Jesus is not on pause just because it is summer, but that He is still pursuing
		us and leading us over these swell days.
	</p>

	<p>
		<a href="mailto:drew@westwoodscc.org">drew@westwoodscc.org</a><br />
		(919) 564-8200 303-279-1616 ext. 2
	</p>

	<iframe
		src="https://calendar.google.com/calendar/embed?src=studentswwcc%40gmail.com&amp;ctz=America%2FDenver"
		frameBorder="0"
		scrolling="no"
		class="studentCalendar"
		title="Student Calendar"
	/>
</div>

<style lang="scss">
	.hero {
		background: #ccc;
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		color: #000;
		padding: 10px 0;
	}
	.studentsLogoContainer {
		width: 250px;
	}
	.container {
		width: 100%;
		max-width: 1170px;
		margin: 30px auto;
		padding: 0 10px;
	}
	.studentCalendar {
		width: 100%;
		height: 800px;
		margin-top: 20px;

		@media (max-width: 801px) {
			height: 95vw;
		}
	}
</style>
