<script>
	import * as Table from '$lib/components/ui/table';
</script>

<div class="flex justify-center">
	<div class="leaderboard">
		<div class="description">
			<h3 class="mt-12 flex justify-center font-orbitron text-xl font-semibold tracking-wider">
				GT3 Season 3 Standings
			</h3>
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

			<Table.Root class="text-md mt-12 font-semibold">
				<Table.Caption>Updated XX/XX/XX</Table.Caption>
				<Table.Header>
					<Table.Row>
						<Table.Head class="w-[100px] text-center">Position</Table.Head>
						<Table.Head class="w-[400px] text-center">Driver</Table.Head>
						<Table.Head class="w-[100px] text-center">Points</Table.Head>
					</Table.Row>
				</Table.Header>
				<Table.Body class="">
					<Table.Row class="">
						<Table.Cell class="font-medium">1</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">ERM_MEHDI59</Table.Cell>
						<Table.Cell class="text-center font-medium">73</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">2</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">DSTINCT_ANDREW</Table.Cell>
						<Table.Cell class="text-center font-medium">68</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">3</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">OP_ROBBYHECK</Table.Cell>
						<Table.Cell class="text-center font-medium">61</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">4</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">DSTINCT_JEEEESH</Table.Cell>
						<Table.Cell class="text-center font-medium">49</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">5</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">OWLS_JMARTI</Table.Cell>
						<Table.Cell class="text-center font-medium">46</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">6</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">OWLS_XUAKO</Table.Cell>
						<Table.Cell class="text-center font-medium">44</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">7</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">WILLIAMLP</Table.Cell>
						<Table.Cell class="text-center font-medium">38</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">8</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">QSD_BELLESI</Table.Cell>
						<Table.Cell class="text-center font-medium">31</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">9</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">GWK_PIDVESAN</Table.Cell>
						<Table.Cell class="text-center font-medium">24</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">10</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">GTS92_SMORENO18</Table.Cell>
						<Table.Cell class="text-center font-medium">22</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">11</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">GTS92_CAIMAN_74</Table.Cell>
						<Table.Cell class="text-center font-medium">22</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">12</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">OP-POPCORN</Table.Cell>
						<Table.Cell class="text-center font-medium">12</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">13</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">QSD_FERREIRA</Table.Cell>
						<Table.Cell class="text-center font-medium">12</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">14</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">JOADSDF_21</Table.Cell>
						<Table.Cell class="text-center font-medium">5</Table.Cell>
					</Table.Row>
					<Table.Row>
						<Table.Cell class="font-medium">15</Table.Cell>
						<Table.Cell class="font-orbitron tracking-wider">CALENJROACH</Table.Cell>
						<Table.Cell class="text-center font-medium">0</Table.Cell>
					</Table.Row>
				</Table.Body>
			</Table.Root>
		</div>
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
</style>
