![Banner](banner.png)

```tsx
import AboutMe from '@components';
import TechnicalSkill from '@components';

const Profile: NextPage = (): JSX.Element => {
  return (
    <>
      <AboutMe
        name="Kevan Yang"
        job="Full stack developer"
        passions={['Coding', 'Anime', 'Video Game', 'Space/Rocket']}
        sports={['Basketball', 'Ice skating', 'Hiking', 'Badminton', 'Table tennis']}
        languages={['French', 'English', 'Cantonese', 'Mandarin']}
      />
      <TechnicalSkill
        languages_framework={[
          'Typescript',
          'Javascript',
          'Node.js',
          'Next.js',
          'React.js',
          'Tailwind CSS',
          'Docker',
          'Python',
          'Java',
          'Sprint Boot',
          'Cypress',
          'Jest',
          'Hurl',
        ]}
        cloud_database={['AWS', 'Supabase', 'PostgreSQL', 'DynamoDB', 'S3 Bucket', 'MongoDB']}
        tool={['VSCode', 'IntelliJ', 'Powershell7', 'WSL2', 'GIT', 'Adobe XD', 'GitHub Actions']}
        devConcepts={['OOP', 'Agile', 'MVC', 'REST', 'Microservice Architecture', 'TDD', 'CI/CD']}
      />
    </>
  );
};

export default Profile;
```
