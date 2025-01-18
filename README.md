class Nury {
	constructor() {
		this.name = 'Tarlan Abdullayev';
		this.position = 'Software Developer';
		this.resume = 'linkedin.com/in/abdullayev-tarlan';
		this.netId = 'abdullayev.tarlan';
		this.techStack = {
			backend: ['C#', 'Node', 'Express', 'Python', 'Django'],
			database: ['SQL Server', 'PostgreSQL', 'MongoDB'],
			frontend: ['HTML', 'CSS', 'Boostrap', 'JavaScript', 'React', 'jQuery'],
			tools: ['Git', 'GitHub', 'Docker', 'UiPath Studio', 'Adobe Xd'],
			salesforce: ['Sales Cloud', 'Service Cloud', 'Apex', 'Visualforce', 'SOQL', 'SOSL']
		};
	}

	getEmail = () => `${this.netId}@northeastern.edu`
}