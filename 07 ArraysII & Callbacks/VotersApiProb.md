
# Voters stats API
This project uses the fetch API (that you're going to learn about later in this course) to get the stats of citizens in a city. To complete this project, you need to return the number of voters in the city selected by the user.

Go to the browser tab and select Amsterdam or Berlin. This will get the age of citizens in the selected city (not real data) using an API. This data is received by a function called getVotersCount.

Implement the getVotesCount function such that it returns the number of citizens that are allowed to vote (must be 18 years or older).

# 1st approach
export function getVotersCount(ages) {
    return ages.filter(function(age){
        return age >= 18;
    }).length;
}

# 2nd approach
export function getVotersCount(ages) {
    const filteredVoters = ages.filter(function(age){
        return age >= 18;
    });
    return filteredVoters.length;
}