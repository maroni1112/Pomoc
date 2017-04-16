package adi.help;

import org.bukkit.plugin.java.JavaPlugin;
import org.bukkit.command.Command;


public class Main extends JavaPlugin{

	public void onEnable(){
		System.out.println("Uruchamianie");
	}

	public void onDisable(){
		System.out.println("Wylaczanie");
	}
	
	public boolean onCommand(org.bukkit.command.CommandSender sender, Command cmd, String label, String[] args) {
	  if(cmd.getName().equalsIgnoreCase("pomoc")){
		  sender.sendMessage("§6Dostepne Komendy");
          sender.sendMessage("§");
		  sender.sendMessage("§4>>§6vip informacje o vipie");
		  sender.sendMessage("§");
		  sender.sendMessage("§4>>§6gildia informacje o gildiach");
		  sender.sendMessage("§4");
          sender.sendMessage("§4>>§cdrop inormacje o dropie");	  
	  }
	return false;
	}
	
}
