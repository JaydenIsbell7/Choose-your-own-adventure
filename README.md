# Choose-your-own-adventure
//variables
int introChoice, middleChoice1, middleChoice2, middleChoice3;
string_t guardian1;
int spendingLimit = randint(20000, 30000);
int days[] = {2, 3, 4, 5};
//6 functions
void roadMap(){
    printf("                                       intro\n\
                      Hawaii                       Antarctica                         Bora Bora\n\
            end1       end2    end3           end1    end2     end3           end1        end2         end3\n\
            Oahu       Maui   Kauai       Kayaking   Cruse helicopter ride  Snorkling     Boat    tubing and parsailing\n");
}

void intro () {
printf ( "Once upon a time, in a magical Oasis there were a guardian. \n");
printf ("Both were very powerful. \n");
printf ("He can teleport you anywhere you want to go. \n") ;
printf ("He notice that two people were teleported into the oasis. \n");
printf ("They ask …What is your name? \n") ;
printf ("The guardian replied.") ;
scanf("%s", &guardian1);
printf ("The guardian then said..Well I got an offer for both of you... \n");
printf("$", spendingLimit, " dollars spending limit for both of you to go anywhere in the world.");
printf ("You can either 1) Go to Hawaii 2) Go to the Bahamas or 3) Bora Bora. \n");
scanf("%i", &introChoice);


    
while(introChoice != 1 && introChoice != 2 && introChoice != 3) {
    printf("That is not a choice. Please choose '1', '2', or '3'\n");
    scanf("%i", &introChoice);
    }
}

    
 void middle1() {
    printf ("You chose the Hawaii. That is a very good choice.\n\
    As promised you get $", spendingLimit ," to go on your dream vacation.\n\
    They left with their $", spendingLimit ," and get to enjoy a nice vacation \n\
    With all the money you and your buddy, both of you get to make a decision\n\
    with your money.");
    printf ("There are three islands of Hawaii that you can choose from 1) Oahu 2) Maui or 3) Kauai. \n");
    scanf("%i", &middleChoice1);

}
void middle2() {
    printf ("You chose Antartica. That is a very good choice.\n\
    As promised you get $", spendingLimit ," to go on your dream vacation.\n\
    They left with their $", spendingLimit ," and get to enjoy a nice vacation \n\
    With all the money you and your buddy, both of you get to make a decision\n\
    with your money.");
    printf ("There are three things you can do in Antartica 1) Kayaking 2) Cruse or 3) helicopter ride. \n");
    scanf("%i", &middleChoice2);

}

void middle3(){
    printf ("You chose the Bora Bora. That is a very good choice.\n\
    As promised you get $", spendingLimit ," to go on your dream vacation.\n\
    They left with their $", spendingLimit ," and get to enjoy a nice vacation \n\
    With all the money you and your buddy, both of you get to make a decision\n\
    with your money.");
    printf ("There are three islands of Hawaii that you can choose from 1) Snorkling 2) Boat ride or 3) tubing and parsailing. \n");
    scanf("%i", &middleChoice3);
}

void Middle1End1(){
    printf("You chose to go to Oahu. We'll start off with going to many different Lookouts.\n");
    printf("We'll look at the water and the pretty land. The weather will be very nice.\n");
    printf("You'll stay at a great hotel for 4 nights and 5 days. This trip will be something\n");
    printf("great for family or friends.");
    exit (1);
    }

void Middle1End2(){
    printf("You choose to go to Maui.\n");
    printf("We will start off the 5 day vacation with snorkeling\nand visits to the beach. We will then go cliff jumping, and on a 5-mile hike.\n");
    printf("We'll go out to many different restaurants. And finish each day with a luau.");
    exit (1);
}

void Middle1End3(){
    printf("You choose to go to Kauai. Kauai has lots of natural beauty and is known for its perfect water.\n");
    printf("We'll start off by going to many beaches, luaus, and shops. Will also go on Hikes to admire\n");
    printf("the land's Beauty. This will be a four-day vacation. You will eat on the beach everyday\n");
    printf("with someone to cook in front of you everyday.");
    exit (1);
}
void Middle2End1(){
    printf("You have chosen to go kayaking. I'm going kayaking in Antarctica.\n");
    printf("You will be surrounded by the brisk water. As your instructor I will take you\n");
    printf("around the popular waterways, And show you around some of the many waterfalls Antarctica\n");
    printf("has to offer. After that we will have races with The Kayaks. And whoever wins the race gets a prize.");
    exit (1);
}
void Middle2End2(){
    printf("You chose to go on a cruise. on this Cruise you'll be able to see lots of sea life and be\n");
    printf("introduced to new parts of Antarctica you probably never heard of. As your instructor\n");
    printf("I'll be taking you on a 3 day cruise to see sea dragoons and mermaids.\n");
    printf("If you fall into the water then I will not be able to get you out because there are many sharks\n");
    printf("and evil mermaids that will eat you for dinner.  Nonetheless this is a very fun vacation.");
    exit (1);
}
void Middle2End3(){
    printf("You have chosen to go for a helicopter ride. Unless the plane's propellers freeze\n");
    printf("due to the cold temperatures you'll be soaring across the ocean in the Antarctica area.\n");
    printf("All fly you over the water and hope not to crash because I don't have a pilot license.\n");
    printf("You'll be able to see whatever you can see from that high up. It's a great experience to do alone or with others.");
    exit (1);
}

void Middle3End1(){
    printf("Discover a window into the underwater world, and explore with unencumbered freedom.\n");
    printf("There's no gear to manage, and no air supplies to monitor on your aquatic adventure.\n");
    printf("Even first timers master the basics of mask and snorkel in short order and are soon immersed\n");
    printf("in the art and sport of the free diver. Let us guide you to the many aquatic\n");
    printf("adventures that await in fish-filled shallows, among colorful coral gardens and in blue water.");
    exit (1);
}
void Middle3End2(){
    printf("Cruising through nebraska. In Goway’s world, you can enjoy the exact same vacation concept\n");
    printf("and much more. If you look at our cruise suggestions, you are bound to find a cruise and\n");
    printf("destination to suit your style and interests.We offer a full range of cruises from the\n");
    printf("traditional larger cruise ships to river cruises, small vessel eco-cruise experiences,\n");
    printf("yacht cruises and small boutique sailing vessels. You can even enjoy a Nebraska safari by boat!\n");
    printf("Cruises range from ", days[rand()%4] ," days up to just under 1 week.");
    exit (1);
}
void Middle3End3(){
    printf("You chose water activities designed for parasailing and newest adventure tubing.\n");
    printf("Parasailing, which, once you get past the thrill of soaring several hundred feet above\n");
    printf("the sea, is actually rather relaxing. With nothing but the peaceful sounds of the breeze\n");
    printf("lifting the parasail, adventurers can relax and unwind while getting a view of Avalon\n");
    printf("normally reserved for the birds.Recently added tubing to its line-up of adventures.\n");
    printf("Open to two or three tubers at a time, this high-speed escapade involves riding an inflatable\n");
    printf("inner tube while being pulled behind a vessel.");
    exit (1);  
}

int main(){
    roadMap();
    intro();
    
    if (introChoice == 1) {
        middle1();
        if (middleChoice1 == 1) {
            Middle1End1();
        }
        if (middleChoice1 == 2) {
            Middle1End2();
        }
        if (middleChoice1 == 3) {
            Middle1End3();
        }
    }
    if (introChoice == 2) {
        middle2();
        if (middleChoice2 == 1) {
            Middle2End1();
        }
        if (middleChoice2 == 2) {
            Middle2End2();
        }
        if (middleChoice2 == 3) {
            Middle2End3();
        }
    }
    if (introChoice == 3) {
        middle3();
        if (middleChoice3 == 1) {
            Middle3End1();
        }
        if (middleChoice3 == 2) {
            Middle3End2();
        }
        if (middleChoice3 == 3) {
            Middle3End3();
        }
    }
    
}
