# Bogdan Gantu

## Contact Info

Str. Cosminului nr.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; gantubogdan@gmail.com

## Summary

I want to learn to be a better developer work in a team with passionate people, and also learn the best practices of working in a team. I have studied programming in University and later better learned it by myself taking a couple of month of work to become a better programmer and get a job in this field.

## Skills

### Programming Languages

Java

- Worked with java for about half a year at a company.

C#

- Working with C# currently for about 3 years now.

Net Core

- developing web applications for a big automotive company to help them manage their employees.

BitBucket

- For version control I have used bitbucket for about 3 years now.

Angular

- Also I have some experience with angular by working on a project for about a year that used angular as front-end.

Jquery

- Jquery is the front end framework that I have used in the past 3 years for my projects.

## Code Examples

     private void InitializeGame(List<Card> cards, List<Player> players)
        {
            List<string> specialCardNames = new List<string> { "Jack", "Queen", "King" };

            for (int i = 2; i <= 11; i++)
            {
                if (i == 11)
                {
                    for (int j = 0; j < 4; j++)
                    {
                        cards.Add(new Card { Name = "Ace", Value = i });
                    }
                    break;
                }
                if(i == 10)
                {
                    for (int j = 0; j < 4; j++)
                    {
                        cards.Add(new Card { Name = i.ToString(), Value = i });
                    }

                    foreach (var cr in specialCardNames)
                    {
                        for (int k = 0; k < 4; k++)
                        {
                            cards.Add(new Card { Name = cr.ToString(), Value = i });
                        }
                    }
                }
                else if(i < 10)
                {
                    for (int j = 0; j < 4; j++)
                    {
                        cards.Add(new Card { Name = i.ToString(), Value = i });
                    }
                }
            }
            ShuffleCardsAndDeal(cards, players);
        }


## Experience

- For my experience I have done some courses on **Coursera** and also **Plurasight** and **Packt** but I do not have code to show for it.
- I project I worked on is a game of [simplified blackjack](https://github.com/EndAroundCarry/Simplified-Blackjack/tree/main) for which I will share the source code.
