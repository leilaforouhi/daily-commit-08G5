def word_count(tex):
    words = text.split()
    return len(words)

if __name__ == "__main__":
    sentence = "Consistency is the key to daily progress"
    print(f"Sentence: {sentence}")
    print(f"Word count: {word_count(sentence)}")
