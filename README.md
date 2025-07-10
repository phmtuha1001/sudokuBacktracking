#include<iostream>
using namespace std;

bool solveMazeUtil(int maze[N][N], int x, int y,int sol[N][N]){
	if (X==N-1&& Y==N-1 && maze[x][y]==1){
		sol[x][y]=1;
		return true;
	}
if (isSafe(maze,x,y)==true){
	
	if(sol[x][y]==1) return false;
	sol[x][y]==1;
	if(solveMazeUtil(maze,x+1,y,sol)==true) return true;
	if(solveMazeUtil(maze,x,y+1,sol)==true) return true;
	if(solveMazeUtil(maze,x-1,y,sol)==true) return true;
	if(solveMazeUtil(maze,x,y-1,sol)==true) return true;
	
	solve[x][y]=0;
	return false;
	}
return false;
}
int main(){
	
	
}
