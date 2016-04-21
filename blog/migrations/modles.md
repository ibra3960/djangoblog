					In our blog

					Features
					========
					Blog will have the following features

					1. Post(Table in database)
					2. Categores(Table in database)
					3. Tag(Table in our database)
					4. Author(Table in our database)

					Let us make a relation betwee our table
					=======================================
					1. Post can have many categories, and a categories can have many post (Relation between Post and Category table)(ManytoMany relation)

					2. a tag can have many post and a post can have many tag(ManytoMany relation)

					3. author can have many posts and a post can have a single author(OneToMany relation) [ no post can write by more than authors]

					Attributes for tables
					=====================
					Post 
					====
					1. title
					2. created_date
					3. image
					4. body
					5. tags
					6. categories
					7. Autor

					Categories
					==========
					1. cat_name
					2. cat_description

					Author
					======
					1. Author name
					2. Author email (not mandatory)
					3. author bio

					tag
					===
					1. tag_name
					2. tag_description
