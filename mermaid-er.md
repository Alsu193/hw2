   mermaid
erDiagram
    USERS ||--o{ POSTS : creates
    USERS ||--o{ COMMENTS : writes
    USERS ||--o{ FAVORITES : saves
    USERS ||--o{ SUBSCRIPTIONS : follows
    POSTS ||--o{ COMMENTS : has
    POSTS ||--o{ POST_CATEGORIES : tagged
    CATEGORIES ||--o{ POST_CATEGORIES : contains
    POSTS ||--o{ FAVORITES : is_saved