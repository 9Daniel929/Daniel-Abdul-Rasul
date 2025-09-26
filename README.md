# PvP Platformer 
using System;

private enum Gamestate { Intro,Mainmenu, Playing, Quit }

class Program
{
    static Gamestate currentGamestate = Gamestate.Intro;
    static void Main( string [] args)
    {
        while (currrentGamestate) != Gamestate.Quit)
        { 
             switch (currenyGamestate)
             { 
                 case Gamestate.Intro:
                     ShowIntro();
                     break;
                case Gamestate.Intro
                    ShowIntro();
                    break;
                case GameState.MainMenu:
                    ShowMainMenu() ;
                    break;
                case Gamestate.Playing:
                    ShowMainMenu() ;
                    break;
                case Gamestate.Playing:
                    //Kill enemys to upgrade your weapons
                      break;
                }
          }
    }

     static void Showintro()
     {
           Console.Clear();
           Console.Writeline("--- Main menu ---");
           Console.Writeline("1. Start Game");
           Console.Writeline("Enter your choice
           var Choice = Console.Readline();

           if  (choice == "1")
           {
                 currentGamestate + Gamestate.Playing
           }
           else if (choice == "2")
           {
                currentGamestate = Gamestate.Quit;
          }
      }
 }

                

                  
                    
                     
