### Hi there, I'm Luiz - aka [Insight-Creator][website] 👋

### Software Developer

[<img align="left" alt="insight-creator.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
[<img align="left" alt="Luiz Mathheus A. Souza | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

<br>
<br>

    class ReadMe:
        def __init__(self, username="Insight-Creator", year=2020):
            self.username = username
            self.name = 'Luiz Matheus A. Souza'
            self.education = {
                'programming': ['Full Stack Web Development', 'Le Wagon'],
                'business': ['BBA, Bachelor of Administration'], 'Pontifícia Universidade Católica - PUC-RIO'],
            }
            self.employment = {
                'developer': ['Brasil', 'Rio de Janeiro'],
            }

        def doing(self, now=2020):
            today = self.year

            if now < today:
                experience = self.employment['Junior Software Developer']
                return """
                Looking for a position! {large_firms} {startups} {remote} in {big_cities}.
                """.format(large_firms=experience[0], big_cities=experience[1])

            elsif now = today:
                dream = self.education['programming']
                return """
                I am currently learning {code} at {code_institute}.
                """.format(code=dream[0], code_institute=dream[1])

            elsif now > today:
                goal = self.employment['developer']
                return """
                Self-Taught Developer Learning Everyday with {projects}.
                projects='software development')
            else:
                return """
                ### Hi there 👋
                """
        def collaborate(self, role, organization, location):
            opportunity = self.employment
            opportunity[role] = [organization, location]

        me = ReadMe(2020)

<br>
<br>
(https://github-readme-stats.vercel.app/api?username=Insight-Creator&show_icons=true&theme=dark&count_private=true)
<br>
<br>

[website]: https://insight-creator.github.io/dev-profile/
[linkedin]: https://www.linkedin.com/in/luiz-affonsosouza/
