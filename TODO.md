# TODO - Building GET API Lab

## Progress Tracking

### Step 1: Update models.py
- [x] Add SerializerMixin to Game, Review, and User models
- [x] Add serialize_rules to prevent circular serialization
- [x] Add association_proxy to Game model for users access

### Step 2: Update app.py
- [x] Add /games route (GET all games)
- [x] Add /games/<int:id> route (GET single game with reviews)
- [x] Add /games/users/<int:id> route (GET users who reviewed a game)

### Step 3: Setup and Test
- [x] Initialize database migrations
- [x] Run migrations
- [x] Seed the database
- [x] Test the API endpoints

## Testing Results
✅ GET /games - Returns all games with reviews and users
✅ GET /games/1 - Returns specific game with reviews and users
✅ GET /games/users/1 - Returns users who reviewed a specific game

