# Norqobulova Dilbar

## Contact Information:

- _Phone number:_ +998 (90)018-17-14
- _Email address:_ ndilbar1618@gmail.com
- _Linkedin profile:_ https://linkedin.com/in/ndn

## Objective:

Friendly, creative, self-motivated Full Stack Web Developer with a half year of experience in building, developing, and managing websites is looking for a part-time frontend or backend job position to gain experience with skilled teammates.

## Skills:

- HTML
- CSS
- SCSS
- Bootstrap
- JavaScript
- Node.js
- Express.js
- PostgreSQL
- SQLite
- Git

## Code example:

**Find the longest common prefix string amongst an array of strings:**

```
/**
 * @param {string[]} strs
 * @return {string}
 */
function commonPrefix (left, right) {
    let min = Math.min(left.length, right.length);
    for (let i = 0; i < min; i++) {
        if ( left.charAt(i) != right.charAt(i) )
            return left.substring(0, i);
    }
    return left.substring(0, min);
}


var getPrefix = function(strs, l, r) {
    if (l === r) {
        return strs[l];
    } else {
        let mid = Math.floor((l + r) / 2);
        let lcpLeft = getPrefix(strs, l, mid);
        let lcpRight = getPrefix(strs, mid + 1, r);
        return commonPrefix(lcpLeft, lcpRight);
    }
}


var longestCommonPrefix = function(strs) {
    if (strs === null || strs.length === 0) return "";

    return getPrefix(strs, 0, strs.length - 1);
};
```

## Experience

- **Uztelecom – Tashkent, Uzbekistan, _April 2021 – September 2021_**

  **Full Stack Web Developer**

  - Participated in the rebuilding process of admin dashboard for Uztelecom's official website using React custom hooks and separation of independent parts into React Components.
  - Integrated PostgreSQL functions and triggers that lead to a 10x reduction of requests to the server. API responses were optimized using Hasura GraphQL.
  - Participated in the development of an internal messenger app in Telegram-like design for a company of more than 200 employees.
  - Implemented the data structure of the Billing system by using Entity Framework Core technology. Covered code with Unit Tests in C#, resulting in 90% test coverage.
  - Developed full stack SPA for job openings platform using NodeJS that features multilanguage database structure support via SQLite. Optimized code quality by 10%.
  - Worked in a team of more than 15 people which included frontend and backend developers and UX/UI designers. Teamwork was managed using Jira software and Git version control system.
