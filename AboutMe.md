
# Chandra Venkata Vijaya Gopal Raju Kalidindi
> I'm gopal raju and I came from india from a city called vizianagaram which is located in andhra pradesh state. I completed my bachelor degree in the year 2022 from computer science field with 7.3 cgpa. I'm here to persue the masters in ACS branch in NorthWest Missouri State University.

![Click he to view my image](https://user-images.githubusercontent.com/122591663/215025369-0e4ba0ad-1a87-457a-a137-d4d98afc80d2.jpg)
 
 ---
 
 ### Tables
 > Here I'am creating the table having some country names that i wanna suggest to the people who want to visit.


 |Country|Reason|Days Spend|
 |---|---|---|
 |Australia|grounds are good|3 Days|
 |canada|winter climate|4 Days|
 |India|Tradition|5 Days|
 |America|Places|4 Days|
 
---

### Quotes

> Imagination is more important than knowledge - *Albert Einstein*

> Everything is theoretically impossible, Until it is done - *Robert A Heinlein*

---

### Code Fencing

> ~~~add_action( 'run_snippet_hourly', function () {
$user_query = array(
    'role'    => 'um_pds-project-manager',
    'orderby' => 'display_name',
    'order'   => 'ASC'
);
$users = get_users( $user_query );
if ( !empty( $users ) ) { 
foreach ( $users as $user ) 
$user_id= $user->ID;
$args = array(
  'posts_per_page' => -1,
  'post_type' => 'project',
  'meta_query' => array(
            'relation' => 'AND',
    array(
        'key'   => 'status',
        'value' => '1'
    ),
         





