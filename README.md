import random

def coin_toss():
    """Simulates a coin toss."""
    outcomes = ['Heads', 'Tails']
    result = random.choice(outcomes)
    return result

if __name__ == '__main__':
    print(coin_toss())
