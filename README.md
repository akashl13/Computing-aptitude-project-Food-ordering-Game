# Computing-aptitude-project-Food-ordering-Game
Food ordered game using C language 
#include <stdio.h>

int main() {
    int choice;

    printf("Welcome to the Food Game!\n");
    printf("What type of food do you want to order?\n");
    printf("1. Pizza\n");
    printf("2. Burger\n");
    printf("3. Salad\n");
    printf("4. Sandwich\n");
    printf("5. Quit the game\n");
    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch (choice) {
        case 1:
            printf("You chose to order a pizza.\n");
            printf("What type of pizza do you want?\n");
            printf("1. Veggie pizza\n");
            printf("2. Meat lovers pizza\n");
            printf("3. Hawaiian pizza\n");
            printf("4. Go back to main menu\n");
            printf("5. Quit the game\n");
            printf("Enter your choice: ");
            scanf("%d", &choice);

            switch (choice) {
                case 1:
                    printf("You ordered a Veggie Pizza.\n");
                    break;
                case 2:
                    printf("You ordered a Meat Lovers Pizza.\n");
                    break;
                case 3:
                    printf("You ordered a Hawaiian Pizza.\n");
                    break;
                case 4:
                    printf("You went back to the main menu.\n");
                    break;
                case 5:
                    printf("You quit the game.\n");
                    break;
                default:
                    printf("Invalid choice!\n");
            }
            break;

        case 2:
            printf("You chose to order a burger.\n");
            printf("What type of burger do you want?\n");
            printf("1. Noodle burger\n");
            printf("2. Chicken burger\n");
            printf("3. Veggie burger\n");
            printf("4. Go back to main menu\n");
            printf("5. Quit the game\n");
            printf("Enter your choice: ");
            scanf("%d", &choice);

            switch (choice) {
                case 1:
                    printf("You ordered a Noodle Burger.\n");
                    break;
                case 2:
                    printf("You ordered a Chicken Burger.\n");
                    break;
                case 3:
                    printf("You ordered a Veggie Burger.\n");
                    break;
                case 4:
                    printf("You went back to the main menu.\n");
                    break;
                case 5:
                    printf("You quit the game.\n");
                    break;
                default:
                    printf("Invalid choice!\n");
            }
            break;

        case 3:
            printf("You chose to order a salad.\n");
            printf("What type of salad do you want?\n");
            printf("1. Garden salad\n");
            printf("2. Caesar salad\n");
            printf("3. Greek salad\n");
            printf("4. Go back to main menu\n");
            printf("5. Quit the game\n");
            printf("Enter your choice: ");
            scanf("%d", &choice);

            switch (choice) {
                case 1:
                    printf("You ordered a Garden Salad.\n");
                    break;
                case 2:
                    printf("You ordered a Caesar Salad.\n");
                    break;
                case 3:
                    printf("You ordered a Greek Salad.\n");
                    break;
                case 4:
                    printf("You went back to the main menu.\n");
                    break;
                case 5:
                    printf("You quit the game.\n");
                    break;
                default:
                    printf("Invalid choice!\n");
            }
            break;

        case 4:
            printf("You chose to order a sandwich.\n");
            printf("What type of sandwich do you want?\n");
            printf("1. Cheese Corn Sandwich\n");
            printf("2. Paneer Sandwich\n");
            printf("3. Grilled Cheese Sandwich\n");
            printf("4. Go back to main menu\n");
            printf("5. Quit the game\n");
            printf("Enter your choice: ");
            scanf("%d", &choice);

            switch (choice) {
                case 1:
                    printf("You ordered a Cheese Corn Sandwich.\n");
                    break;
                case 2:
                    printf("You ordered a Paneer Sandwich.\n");
                    break;
                case 3:
                    printf("You ordered a Grilled Cheese Sandwich.\n");
                    break;
                case 4:
                    printf("You went back to the main menu.\n");
                    break;
                case 5:
                    printf("You quit the game.\n");
                    break;
                default:
                    printf("Invalid choice!\n");
            }
            break;

        case 5:
            printf("You quit the game.\n");
            break;

        default:
            printf("Invalid choice! Please select between 1 and 5.\n");
    }

    return 0;
}
