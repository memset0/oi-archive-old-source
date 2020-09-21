
# Content

Jumping Jack is in charge of organizing a ash mob. The members of the ash mob move around town all day and part of the appeal of this group is they come together to do their thing whenever the mood strikes Jack. When the mood does strike, Jack sends a text message to the members to meet at a particular intersection in town in exactly one hour. The streets of the town run only north-south or east-west and are evenly spaced, forming a perfect grid like a sheet of graph paper. Due to the spontaneity,
Jack wants to minimize the inconvenience and so picks an intersection to minimize the total distance traveled by the ash mob's members. Fortunately Jack has the locations of all the members via the GPS on their cell phones. Your job is to $2\_{nd}$ the meeting location given all the members' locations.

Each intersection will be given by a pair of non-negative integers; the rst coordinate is the east-west street and the second coordinate is the north-south street. The location of each ash mob member will be an intersection. Members can travel only north-south or east-west between intersections.

For example, suppose there are $5$ mob members at locations $(3,4)$; $(0,5)$; $(1,1)$; $(5,5)$ and $(5,5)$. Then if Jack summons them all to location $(3,5)$, the total number of blocks traveled by the mob members would be $14$. Jack could do no better { but sometimes the `best` location may not be unique

# Standard Input

Input for each test case will be a series of integers on one or more lines. The first integer, $n$ ($1 \leq n \leq 1000$), indicates the number of mob members. There follow n pairs of integers indicating the location (intersection) of each member. The location coordinates are both between $0$ and $10^6$, inclusive. More than one member may be at the same intersection. A line containing $0$ will follow the last test case.

# Standard Output

Output one line for each test case in the format given below. The ordered pair is the coordinates of the location in the city where the total distance traveled (in blocks) is minimal. If there is more than one such location, output the one with the smallest first coordinate. If there is more than one `best` location with the smallest first coordinate, output the one of those with the smallest second coordinate.

The total number of blocks traveled by all the mob members follows the location.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>5 3 4 0 5 1 1 5 5 5 5
4 100 2 100 2 100 2 1 20000
0</td><td>Case 1: (3,5) 14
Case 2: (100,2) 20097</td></tr></table>


# Constraints



# Note



# Source


