# Database-project

#Schema
-- TABLE OF PLAYERS INFO
-- CREATE TABLE players (id INTEGER PRIMARY KEY, name TEXT, position id, team id);

-- #TABLE OF TEAMS
CREATE TABLE team (id SERIAL PRIMARY KEY, name TEXT);

INSERT INTO team (name) VALUES ('Guelph');
INSERT INTO team (name) VALUES ('Kitchener');
INSERT INTO team (name) VALUES ('Toronto');              
INSERT INTO team (name) VALUES ('Kingston');                     
                     
-- TABLE OF PLAYER POSITIONS
CREATE TABLE position (id SERIAL PRIMARY KEY, name TEXT);
 
INSERT INTO position (name) VALUES ('Point Guard');
INSERT INTO position (name) VALUES ('Shooting Guard');                   
INSERT INTO position (name) VALUES ('Small Forward')
INSERT INTO position
-- TABLE OF INDIVIDUAL MATHCUPS BETWEEN TEAMS 
-- CREATE TABLE match (id INTEGER PRIMARY KEY, team1 TEXT, team2 TEXT, winning team TEXT, date CURRENT_DATE);

-- TABLE OF MATCH SCORES
-- CREATE TABLE matchscore (match id, score TEXT)

-- TABLE OF PLAYER STATS PER MATCH
-- CREATE TABLE playerstats (player id, match id, shots attempted INTEGER, shots made INTEGER, minutes played TIME, fouls INTEGER, turnovers INTEGER, assists INTEGER, steals INTEGER)

-- TABLE OF 2 POINT SHOTS
-- CREATE TABLE 2pointers (time, location INTEGER)

-- TABLE OF 3 POINT SHOTS 
-- CREATE TABLE 3pointers (time, location INTEGER)

-- TABLE OF FREE THROWS
-- CREATE TABLE freethrows (time, number of shots INTEGER, made shots INTEGER,

#Query

-select name from team;
-select name from Player position

select TEAM.name || ' ' || TEAM.id, PLAYER POSITION.name || ' ' || PLAYER POSITION.id as 

