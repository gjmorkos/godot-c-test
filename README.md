# godot-c-test
using Godot;
using System;

[GlobalClass]
public partial class FirstNode : Node
{
	[Export]
	int health = 100;
	public override void _Ready()
	{
		GD.Print("FirstNode is ready with health: " + health);
	}
}
