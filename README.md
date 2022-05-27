# OSGeo-Assignment

GMT352_1_2122B 

Scenario & context: STARS
I recorded the names, colors, id and epoch for 4 different epochs referenced in the 4 seasons of 2022, and the information I obtained for the last epoch I observed.


*First of all, I created the table containing the names of the stars I observed, thanks to postgres.

create table stars_name
( name_en character varying(30),
  name_st character varying(30),
  CONSTRAINT star_name_pkey PRIMARY KEY (name_en));
  
 insert into star_name(name_en_,name_st) values
('sirius','vega'),
('capella','rigel');


*Then I created a table for the id, epoch and color of the stars.

CREATE TABLE stars
create extension postgis;
(s_type character varying(30),
 color real,
 id serial,
 observation_time timestamp,
 CONSTRAINT star_pkey PRIMARY KEY (id);
 
 
 https://addons-sso.heroku.com/apps/141a93b1-e4f7-4417-8944-5f0b91ab224b/addons/8c469d03-20bb-4923-b132-8e3f99920a7a
 https://dashboard.heroku.com/apps/planetzoe
