<script>
	import * as Table from '$lib/components/ui/table';
</script>

<div class="leaderboard">
	<div class="description">
		<h3 class="mt-12 flex justify-center">GT3 Season 3 Standings</h3>
		<!-- <table>
					<thead>
						<tr>
							<td>Position</td>
							<td>Driver</td>
							<td>Points</td>
						</tr>
					</thead>
					<tbody>
						<tr>
							<td>1</td>
							<td>ERM_MEHDI59</td>
							<td>72</td>
						</tr>
						<tr>
							<td>2</td>
							<td>DSTINCT_ANDREW</td>
							<td>68</td>
						</tr>
						<tr>
							<td>3</td>
							<td>OP_ROBBYHECK</td>
							<td>61</td>
						</tr>
						<tr>
							<td>4</td>
							<td>DSTINCT_JEEEESH</td>
							<td>49</td>
						</tr>
						<tr>
							<td>5</td>
							<td>OWLS_JMARTI</td>
							<td>46</td>
						</tr>
						<tr>
							<td>6</td>
							<td>OWLS_XUAKO</td>
							<td>44</td>
						</tr>
						<tr>
							<td>7</td>
							<td>WILLIAMLP</td>
							<td>38</td>
						</tr>
						<tr>
							<td>8</td>
							<td>QSD_BELLESI</td>
							<td>31</td>
						</tr><tr>
							<td>9</td>
							<td>QWK_PIDVESAN</td>
							<td>68</td>
						</tr>
						<tr>
							<td>10</td>
							<td>GTS92_SMORENO18</td>
							<td>22</td>
						</tr>
						<tr>
							<td>11</td>
							<td>GTS92_CAIMAN_74</td>
							<td>22</td>
						</tr>
						<tr>
							<td>12</td>
							<td>OP_POPCORN</td>
							<td>12</td>
						</tr>
						<tr>
							<td>13</td>
							<td>QSD_FERREIRA</td>
							<td>12</td>
						</tr>
						<tr>
							<td>14</td>
							<td>JOADSDF_21</td>
							<td>5</td>
						</tr>
						<tr>
							<td>15</td>
							<td>CALENJROACH</td>
							<td>0</td>
						</tr>
					</tbody>
				</table> -->

		<Table.Root class="mt-12">
			<Table.Caption>Updated XX/XX/XX</Table.Caption>
			<Table.Header>
				<Table.Row>
					<Table.Head class="w-[100px] text-center">Position</Table.Head>
					<Table.Head class="text-center">Driver</Table.Head>
					<Table.Head class="w-[100px] text-center">Points</Table.Head>
				</Table.Row>
			</Table.Header>
			<Table.Body class="justify-center">
				<Table.Row class="">
					<Table.Cell class="font-medium">1</Table.Cell>
					<Table.Cell>ERM_MEHDI59</Table.Cell>
					<Table.Cell class="text-center">73</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">2</Table.Cell>
					<Table.Cell>DSTINCT_ANDREW</Table.Cell>
					<Table.Cell class="text-center">68</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">3</Table.Cell>
					<Table.Cell>OP_ROBBYHECK</Table.Cell>
					<Table.Cell class="text-center">61</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">4</Table.Cell>
					<Table.Cell>DSTINCT_JEEEESH</Table.Cell>
					<Table.Cell class="text-center">49</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">5</Table.Cell>
					<Table.Cell>OWLS_JMARTI</Table.Cell>
					<Table.Cell class="text-center">46</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">6</Table.Cell>
					<Table.Cell>OWLS_XUAKO</Table.Cell>
					<Table.Cell class="text-center">44</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">7</Table.Cell>
					<Table.Cell>WILLIAMLP</Table.Cell>
					<Table.Cell class="text-center">38</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">8</Table.Cell>
					<Table.Cell>QSD_BELLESI</Table.Cell>
					<Table.Cell class="text-center">31</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">9</Table.Cell>
					<Table.Cell>GWK_PIDVESAN</Table.Cell>
					<Table.Cell class="text-center">24</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">10</Table.Cell>
					<Table.Cell>GTS92_SMORENO18</Table.Cell>
					<Table.Cell class="text-center">22</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">11</Table.Cell>
					<Table.Cell>GTS92_CAIMAN_74</Table.Cell>
					<Table.Cell class="text-center">22</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">12</Table.Cell>
					<Table.Cell>OP-POPCORN</Table.Cell>
					<Table.Cell class="text-center">12</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">13</Table.Cell>
					<Table.Cell>QSD_FERREIRA</Table.Cell>
					<Table.Cell class="text-center">12</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">14</Table.Cell>
					<Table.Cell>JOADSDF_21</Table.Cell>
					<Table.Cell class="text-center">5</Table.Cell>
				</Table.Row>
				<Table.Row>
					<Table.Cell class="font-medium">15</Table.Cell>
					<Table.Cell>CALENJROACH</Table.Cell>
					<Table.Cell class="text-center">0</Table.Cell>
				</Table.Row>
			</Table.Body>
		</Table.Root>
	</div>
</div>

<style>
	.leaderboard {
		max-width: 55em;
		margin-right: auto;
		margin-left: auto;
		display: block;
		padding: 1em;
		padding-top: 2em;
	}
	.description {
		display: inline-block;
		text-align: center;
		margin: 1em;
		color: white;
		transform: translateY(-5em);
	}
	table {
		margin-top: 2em;
		width: 70vh;
		color: white;
		margin-right: auto;
		margin-left: auto;
	}
	table thead {
		opacity: 0.8;
	}
	table img {
		width: 2em;
		height: 2em;
		border-radius: 100%;
	}
</style>
